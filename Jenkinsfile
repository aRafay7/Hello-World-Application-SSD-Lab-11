pipeline {
agent any
  environment{
    NEW_VERSION = '1.3.0'
  }
  tools{
    maven "Maven"
  }
stages {
stage(&#39;Build&#39;) {
steps {
echo &#39;Building..&#39;

// Here you can define commands for your build
}
}
stage(&#39;Test&#39;) {
steps {
echo &#39;Testing..&#39;
// Here you can define commands for your tests
}
}
stage(&#39;Deploy&#39;) {
steps {
echo &#39;Deploying....&#39;
// Here you can define commands for your deployment
}
  stage("test"){
    steps {
      when{
        expression{
          flag = = false
        }
      }
      echo "testing project"
    }
}
}
}
