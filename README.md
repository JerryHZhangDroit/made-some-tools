# made-some-tools
made some tools 

## replaceLinks.sh

takes in an "old link to new link mapping csv or txt file" and a location to all mandate json files and replaces the old links in the mandates with the new links. 

i.e.

./replaceLinks bofa-mifir-links.csv path/to/snapshot.droit.1.0 

will create an output file /Scripts/affectedFiles.txt, which shows all the files that have been modified by the script, and replace all the old links in the mandates with the new links shown in the *bofa-mifir-links.csv*
