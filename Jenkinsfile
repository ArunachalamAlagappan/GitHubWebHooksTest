pipeline{
agent any
stages
{
stage("Code Checkout")
{
steps
{
echo "Testing Code checkout"
}
}
stage("Code compilation")
{
steps
{
sh "javac WebhooksExampleNew.java"
}
}
stage("Code Execution")
{
steps
{
sh "java WebhooksExampleNew"
}
}
}
}
}