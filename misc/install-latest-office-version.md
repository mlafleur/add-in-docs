# Install the latest version of Office 2016

New developer features, including those still in preview, are delivered first to subscribers that opt-in to get the latest builds of Office. To get the latest builds of Office 2016: 

Office 365 Home, Personal and University Subscribers:Insiders Program

Office 365 Commercial customers: First Release Build

For either program, the build is the same. To deploy it follow these simplified steps: 
1. Download the Office 2016 Deployment Tool. 
2. Run the tool, this will extract 2 files. Setup.exe and configuration.xml.
3. Replace the configuration file with this First Release Configuration File.
4. From an elevated command prompt (Run as admin) run:  setup.exe /configure configuration.xml 

Once the installation process completes you will have the latest Office 2016 applications installed. You can verify the build installed by going to File>Account from any of the Office applications. 

To verify you have the latest build, look for the (Office Insiders) label under the version number on the Product information page.