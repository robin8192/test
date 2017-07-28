
node {

load "${env.WORKSPACE}@script\\vars.txt"

echo "${env.TEST123}"
echo env.TEST123


echo "${VAR_A}"
echo "job: ${env.JOB_NAME}"

int i = 1
Boolean NO_ERROR = true
String FOUND_ROLE

while (NO_ERROR) {
     try {
        FOUND_ROLE = ${"ROLE" + ${i}}

       echo FOUND_ROLE
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
