# udacity-network
network infrastructure for udacity using cloud-formation
### Architecture

  ![network- architecture](https://user-images.githubusercontent.com/94189602/212002305-2484fcec-d0ff-410c-a796-166c8b5b21c6.PNG)

### Usage
### Make sure you have the following installed:

* [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)

### Set up your AWS credentials:

            aws configure
      
### To create the infrastructure, run the following command:
            
            # Create the infrastructure
            # Clone the repo
            git clone https://github.com/mustafaDevop/udacity-network

            # Change directory
            cd high-availability-web

            # Make the script executable
            sudo chmod +x create-servers.sh

            # Run the script, replace {stack-name} with your own stack name
            ./create-servers.sh {stack-name}


### To update the infrastructure, run the following command:
            
            # Make the script executable
            sudo chmod +x update-servers.sh

            # Run the script, replace {stack-name} with your own stack name
            ./update.sh {stack-name}
  
### To delete the infrastructure, run the following command:
                  
                  # Make the script executable
                  sudo chmod +x delete-servers.sh

                  # Run the script, replace {stack-name} with your own stack name
                  ./delete.sh {stack-name}
