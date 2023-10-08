# spin
SPIN (Simple Package INstaller) is a completely open application sharing program for free software.
SPIN uses electron for the GUI (Graphical User Interface) and C for the CLI tool that downloads the program. When uploading a program, you must enter the application data to the "pkglist.json" file in
the "application" object in this exact format:
{
  app_name: "Application name goes here",
  app_description: "Application description goes here",
  installer_download_url: "Application installer URL goes here",
}
