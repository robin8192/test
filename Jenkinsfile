
node {

load "${env.WORKSPACE}@script\\vars.txt"

echo "${env.TEST123}"
echo "${VAR_A}"
echo "job: ${env.JOB_NAME}"

def i = 1
def NO_ERROR = true

while (NO_ERROR) {
     try {
       echo ROLE1
     }
     catch(e){
       echo "oh no: " + e
       NO_ERROR = false
     }
     i++
}


// echo "${ROLE1}"
// echo "${ROLE2}"
// echo "${ROLE3}"


    echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
}
