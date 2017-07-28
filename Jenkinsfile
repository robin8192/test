load %WORKSPACE%\testpipeline@script\vars.txt

echo ${env.TEST123}
echo ${TEST123}
echo "job: ${env.JENKINS_JOB}"

node {
    print ${env.TEST123}
    echo ${env.TEST123}
    echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
}