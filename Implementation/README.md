# Perfect Paws Application

Perfect Pets is the ultimate pet adoption app, providing an easy and secure login experience. Discover a diverse range of adorable pets with personalized profiles, complete with photos and unique info about each pet. Add your favorites to the shopping cart, and seamlessly complete the adoption process. It's as easy as selecting your perfect companion, placing them in your cart, and completing the order and delivery information. Perfect Pets is your quick and easy path to finding the perfect pet.

**Environment Requirments:**

The application is compatible with the following environments:

  + Windows: Versions: Windows 7, Windows 8, Windows 10, and later.

  + MacOS

  + Linux

Ensure that the Java Runtime Environment (JRE) is installed on the system and that SceneBuilder is integrated in the buildpath of JavaFX to run Perfect Pets successfully. The application's cross-platform compatibility ensures a consistent and enjoyable user experience across a diverse range of operating systems.

## Steps to clone & build the application

  + ### Prerequisites
    
      + Java Development Kit (JDK) installed on your machine.
        
      + Maven installed.
        
      + JavaFX installed.
        
      + SceneBuilder for designing UI if required.
        
      + Ensure that your machine meets the system requirements mentioned earlier (Windows, MacOS, or Linux).

   
  + ### Step 1: Clone the Repository
    
      + Link to repository found in this file [here](Perfect-Paws-Application.md)
        
          + Navigate to the main page of the repository. Above the list of files, click **<> Code**.
          + Copy the URL for the repository.
          + Open Terminal or an IDE of your choosing
          + Change the current working directory to the location where you want the cloned directory.
          + Type git clone, and then paste the URL you copied earlier.
              + **git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY**
          + Press enter to create your clone.


  + ### Step 2: Dependencies
      + Ensure JDK is installed and JAVA_HOME is set.
      + Make sure Maven is installed. If not, you can download it from the official Apache Maven website.
      + Ensure JavaFX is installed. If not, download and set it up based on your operating system. Ensure that the JavaFX binaries are in your system's PATH.
      + JSON should already be in the .xml file


  + ### Step 3: Build the Application
      + mvn clean install
          + This command will download dependencies, compile the source code, and build the PerfectPaws application. Ensure that the build completes successfully without any errors.


  + ### Step 4: Run the Application 
      + mvn javafx:run
          + This command will launch the PerfectPaws application. Ensure that the application starts without any issues.
              + If not their may be some issues with the build path of the class so issue everything is installed 


  + ### Step 5: Database Setup
      + Ensure that the necessary JSON files or data are present. Check for any provided scripts or instructions in the repository.
          + All files should be present in the repository


  + ### Step 6: Opening UI in SceneBuilder
      + SceneBuilder is used for UI design, open it and load the FXML files from the src/main/resources directory.
          + If you don't have SceneBuilder downloaded
              + Visit the official SceneBuilder download page: [Gluon SceneBuilder](https://gluonhq.com/products/scene-builder/)
              + Choose the appropriate version for your operating system (Windows, macOS, or Linux) and download the installer.
              + Configure SceneBuilder in your IDE (Optional):
                  + If you're using an integrated development environment (IDE) like IntelliJ IDEA or Eclipse, you may need to configure the path to SceneBuilder in your IDE settings.       

  + **Important Notes:**
      + Ensure that JavaFX is correctly configured in IntelliJ IDEA. You may need to set the VM options in the Run Configuration to include the JavaFX modules.
      + This application was compiled and created using IntelliJ
          +  + SceneBuilder is used for UI design, you can open it from within IntelliJ IDEA. Go to Preferences/Settings > Languages & Frameworks > JavaFX, and set the path to your SceneBuilder.

        
   
    
  

