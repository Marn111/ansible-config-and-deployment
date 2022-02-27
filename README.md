
***Prerequsite:

- Before running ansible-config-and-deployment in Circle.ci, an EC2 instance must be running by using key name 'udacity'. 

- If not, run ansible-create-infra on Circle.ci first.

- Go to CircleCI Project Settings --> SSH Keys > Additional SSH Keys, and paste the paste the SSH key here [https://circleci.com/docs/2.0/add-ssh-key/].

// While adding SSH key
  - `Host name`: must be blank
  - Copy private key from udacity.pem file
  - `Private Key`: Make sure! no other special charactors behind private key string

