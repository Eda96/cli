# cli
 How do I create a hidden file or folder? How do I display it in the CLI?

$touch sample.txt >> created a file
$mv sample.txt .sample.txt  >> the file has hidden

$ls >> not display hidden files
$ls -a >>display hidden files 


How do I create multiple nested directories, like /c/Users/myusername/these/folders/are/cli.txt

$ mkdir -p /c/Users/myusername/these/folders/cli.txt


How do I append a message to a file, without a newline character?

$echo "first massage"  
$echo -n "second message"
