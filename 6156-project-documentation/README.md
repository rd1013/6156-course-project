Usage is similar to the base project, so the top level README.md instructions apply.

For my project, I specifically looked at the AST representation, so I added a set of data extraction and
model training scripts in the same format as the rest of the project.

After following the installation instructions:

### Downloading and extracting AST data
cd to "data/java-sbt"
run: "bash get_data.sh"

### Training the model
cd to "scripts/java-sbt"
* run: "bash transformer.sh [x] [model_name]"
* replace [model_name] with a string of your choice
* the [x] determines which device to use; -1 = CPU, 0 = GPU0, 1 = GPU1, etc.; you can pass "0,1" to use the first and second GPU
  * e.g. "bash transformer.sh 0,1 sbt2javadoc"
    
The shell script itself contains the configuration and parameters to adjust things like maximum training epochs, epochs to wait before stopping early,
batch sizes, etc. I typically ran my model on an RTX 3090 with batchsize=48. 
