# cash-register-unit1
AP Java Unit 1 project

Add the following to your tasks.json:

{
    "tasks": [
        {
            "type": "che",
            "label": "cash-register-unit1:maven build and run",
            "command": "mvn -Duser.home=${HOME} -f ${CHE_PROJECTS_ROOT}/cash-register-unit1 clean install \njava -jar ${CHE_PROJECTS_ROOT}/cash-register-unit1/target/*.jar",
            "target": {},
            "previewUrl": "",
            "problemMatcher": []
        }
    ]
}
