#SAN Commands Generator
The tool is used to automatically generate CLI configuration commands for both Cisco and Brocade SAN switches. 

#Description
SAN Commands Generator helps systems administrators “SAN Administrators” to automatically generate CLI commands without having to write everything manually. It would help with the following. 

• Building SAN configuration from scratch-up in large scale datacenters. 

• Gets you up to speed while configuring SAN switches, in case your are not very familiar with the commands.         

• Avoiding some of the normal CLI human mistakes “e.g. leaving space at the end of the WWPN/aliases”. 

#Installation
The tool was built with Java, it initially requires JVM to run, you just need to open the .jar file and the tool should open normally. All the required libraries are associated, and should not be removed, otherwise the tool will fail.

#Usage Instructions
The SAN administrator should fill in the required info in the excel templates provided with the package “Excel temples for both Brocade and Cisco”, then you will have to follow the below steps.
- Open the tool and fill the required data.
	- Switch type.
  - Input file path “The path to the Excel”.
  - Output directory. 
  - Output text file name.
-	The output file should be opened with notepad++ or similar text editing tools.

#Licensing
Licensed under the Apache License, Version 2.0 (the “License”); you may not use this file except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0
Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an “AS IS” BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

#Support
Please file bugs and issues at the Github issues page. For more general discussions you can contact the EMC Code team at Google Groups or tagged with EMC onStackoverflow.com. The code and documentation are released with no warranties or SLAs and are intended to be supported through a community driven process.

