# Flutter apps build

Testing on How to make iOS CI/CD using flutter

## Getting Started

Setting Up CI/CD for Flutter Ios
Source: https://www.youtube.com/watch?v=mQMy12Sk0xM

1.

If new project / repository
- Create repository  
- in Github - click on Action Tab and search Dart and configure
- Change the yaml settings as below
https://github.com/AmirBayat0/iOS_iPA/blob/main/.github/workflows/dart.yml
- clone the project, and create flutter project inside the clone project

If exist project / repository
- Go to project.
- create a folder -> .github/workflows
- create a file inside the folder above name dart.yaml
- paste the code
https://github.com/AmirBayat0/iOS_iPA/blob/main/.github/workflows/dart.yml

2.

- Go to project on github and select settings tab
- On the left, select Actions > General
- Check on Workflow permission to allow Read and write permissions and save
- Go back to Action tab above
- On the left side, click on the iOS-ipa-build
- run work flow on the right
