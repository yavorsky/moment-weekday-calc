1. Update bower.json and package.json

2. Build the project:
>grunt

3. Commit changes

4. Push a tag  
>git tag -a 1.0.5 -m'1.0.5 release descr'  
>git push origin 1.0.5

5. Do a release on github:  
tags->Add release notes onto latest

6. npm publish

7. the last tag is released to bower automatically
