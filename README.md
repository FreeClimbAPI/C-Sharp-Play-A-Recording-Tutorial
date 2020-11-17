# C# - Play a Recording Tutorial

This project serves as a guide to help you build an application with FreeClimb. View this tutorial on [FreeClimb.com](https://docs.freeclimb.com/docs/play-a-recording#section-c). Specifically, the project will:

- Play a recording to a caller during a call.

## Setting up your new app within your FreeClimb account

To get started using a FreeClimb account, follow the instructions [here](https://docs.freeclimb.com/docs/getting-started-with-freeclimb).

## Setting up the Tutorial

1. Install the nuget packages necessary using command:

   ```bash
   $ dotnet add package freeclimb-cs-sdk
   ```

2. Configure environment variables

   | ENV VARIABLE            | DESCRIPTION                                                                                                                                                                             |
   | ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
   | RECORDING_URL | The  url where FreeClimb can download a recording to play. The recording must be [formatted correclty](https://docs.freeclimb.com/reference/interactive-voice-response-ivr#play) to work with FreeClimb. Recordings made by FreeClimb during other calls can be played by using the url provided in the [recordings page](https://www.freeclimb.com/dashboard/portal/recordings). |

## Runnning the Tutorial

1. Run the application using command:

   ```bash
   $ dotnet run
   ```

## Getting Help

If you are experiencing difficulties, [contact support](https://freeclimb.com/support).
