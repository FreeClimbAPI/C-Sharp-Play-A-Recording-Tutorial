# C# - Play a Recording Tutorial

This project serves as a guide to help you build an application with FreeClimb. Specifically, the project will:

- Play a recording to a caller during a call.

## Setting up your new app within your FreeClimb account

To get started using a FreeClimb account, follow the instructions [here](https://persephony-docs.readme.io/docs/getting-started-with-persephony).

## Setting up the Tutorial

1. Install the nuget packages necessary using command:

   ```bash
   $ dotnet add package freeclimb-cs-sdk --version 1.0.0.1
   ```

2. Configure environment variables

   | ENV VARIABLE            | DESCRIPTION                                                                                                                                                                             |
   | ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
   | RECORDING_URL | The  url where FreeClimb can download a recording to play. The recording must be [formatted correclty](https://docs.persephony.com/reference/interactive-voice-response-ivr#play) to work with FreeClimb. Recordings made by FreeClimb during other calls can be played by using the url provided in the [recordings page](https://www.persephony.com/dashboard/portal/recordings). |

## Runnning the Tutorial

1. Run the application using command:

   ```bash
   $ dotnet run
   ```
