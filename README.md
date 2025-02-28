### chrisy-ass-2-8
Assignment 2-8 
Create a public Github repository containing: Modified sample codebase that was deployed to Elastic Beanstalk as the new version Readme file that includes the cli commands used to create the new version package bundle

### CLI commands to create the new version package bundle
```
sudo apt install zip
mkdir eb_python
cp python.zip eb_python
cd eb_python
unzip python.zip
nano application.py
zip -d python.zip application.py
zip python.zip application.py

git clone https://github.com/yeoHomeyeo/chrisy-ass-2-8.git
cp application.py chrisy-ass-2-8
cd chrisy-ass-2-8
git add .
git commit -m "only application.py"
git push

```

### The modified code
```
</head>
<body id="sample">
  <div class="textColumn">
    <h1>Sample app in Development Environment by Chris Yeo</h1>
    <p>Your first AWS Elastic Beanstalk Python Application is now running on your own dedicated environment in the AWS Cloud</p>
    <p>This environment is launched with Elastic Beanstalk Python Platform</p>
  </div>
```
