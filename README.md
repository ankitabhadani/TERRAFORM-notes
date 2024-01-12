# TERRAFORM-notes
#what is terraform
## Terraform is a powerful Infrastructure as Code (IaC) tool that allows you to define and provision infrastructure in a declarative manner. 
## it supportsa multi cloud providers(AWs,azure,etc)
## Declarative Syntax: You define the desired state of your infrastructure in a configuration file 

****************************************************************************
# terraform install on linux 
   # Download Terraform
wget https://releases.hashicorp.com/terraform/<version>/terraform_<version>_linux_amd64.zip

# Unzip the downloaded file
unzip terraform_<version>_linux_amd64.zip

# Move the binary to a directory in your PATH
sudo mv terraform /usr/local/bin/

# Verify the installation
terraform version

******************************************************************************
## Installing Terraform on Windows

Follow these steps to install Terraform on a Windows machine:

1. **Download Terraform:**
   - Visit the [Terraform Downloads](https://www.terraform.io/downloads.html) page.
   - Download the Windows version of Terraform.

2. **Extract the Zip Archive:**
   - Extract the downloaded zip file to a directory of your choice (e.g., `C:\Program Files\terraform`).

3. **Add Terraform to the System Path:**
   - Right-click on `This PC` or `Computer` on your desktop or in File Explorer.
   - Select `Properties`.
   - Click on `Advanced system settings`.
   - Click on `Environment Variables`.
   - Under `System variables`, find the `Path` variable and click on `Edit`.
   - Click on `New` and add the path to the directory where the Terraform executable (`terraform.exe`) is located.

4. **Verify the Installation:**
   - Open a new Command Prompt or PowerShell window.
   - Run the following command to verify the installation:
     ```bash
     terraform --version
     ```
   - This should display the installed Terraform version.

Now you have successfully installed Terraform on your Windows machine.
