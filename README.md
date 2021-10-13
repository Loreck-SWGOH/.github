# .github

Follow these steps to avoid having the double directory listing that results from simply saving an Eclipse project in GitHub.

On GitHub, create a new repository. Add a README, License, and .gitignore

In Eclipse, ensure that you DO NOT have a project with the same name as this project. Select File -> Import Open Git, select Projects from Git (with smart import) Select Clone URI Copy and paste URI from repository Select the branch Change the location of the local repository if needed Finish

Right click the Eclipse project Select Project Natures and Add Java Apply and Close

Right click the Eclipse project Select Build Path -> Add Libraries ... Add JRE System Library and JUnit (may have to do this separately)

If you have an exising project copy the relevant files into the new project.

If this is a new project, create a new source folder, then create Java packages within this source folder.
