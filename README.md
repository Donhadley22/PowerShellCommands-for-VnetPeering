# Azure PowerShell VNet Peering

This PowerShell script automates the process of creating and peering two Azure Virtual Networks (VNets) using Azure PowerShell.
It is a simple and straightforward way to set up network peering between VNets for secure and efficient communication.

## Prerequisites
Before you begin, ensure you have the following prerequisites in place:

- An active Azure subscription
- Azure PowerShell module installed (you can install it using `Install-Module -Name Az`)
- Appropriate permissions to create and manage resources in your Azure subscription

## Usage
1. Clone this repository or download the script.
2. Open a PowerShell terminal.
3. Sign in to your Azure account using `Connect-AzAccount` if you haven't already.

## Script Details
The script performs the following actions:

Creates two Azure VNets, Vnet1 and Vnet2, in the specified resource groups.
Configures subnets within each VNet.
Establishes a VNet peering connection from Vnet1 to Vnet2.

## Customization
You can customize the script by modifying the parameters and configurations within the script file.
For example, you can change VNet names, address spaces, and subnets to fit your specific requirements.

## Contributing
If you have suggestions, bug reports, or would like to contribute to this project, please feel free 
to open an issue or create a pull request. We welcome your input!

## License
This project is licensed under the MIT License; see the LICENSE file for details.
