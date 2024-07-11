#test
`wget -O demo.zip https://start.spring.io/starter.zip?type=maven-project&language=java&bootVersion=3.3.1&baseDir=demo&groupId=com.example&artifactId=demo&name=demo&description=Demo%20project%20for%20Spring%20Boot&packageName=com.example.demo&packaging=jar&javaVersion=17&dependencies=lombok,web`


# Step 1: Use wget to download the file and save it as demo.zip
wget -O demo.zip "https://start.spring.io/starter.zip?type=maven-project&language=java&bootVersion=3.3.1&baseDir=demo&groupId=com.example&artifactId=demo&name=demo&description=Demo%20project%20for%20Spring%20Boot&packageName=com.example.demo&packaging=jar&javaVersion=17&dependencies=lombok,web"

# Step 2: Unzip the archive to the current directory
unzip demo.zip -d .

# Step 3: Move the contents to the current directory
mv demo/* demo/.* .

# Step 4: Remove the temporary directory
rmdir demo