# MusicDiscovery

MusicDiscovery is a full stack web application created using C# and ASP.NET Core Frameworks. Using the MusicBrainz API, Users will be able to discover music information based on area, artist, event, genre, instrument, label, place, recording, release, release-group, series, work, or a MusicBrainz url. 

User's will be able to make a collection of subjects they are interested in, and can write reviews for artists, event, genre, recording, release-group, series, or work.

TODO:
- set up controller for entities

## Dependencies

Currently I'm using the MusicBrainz .NET client libraries for web search and cover art. The NuGet packages can be downloaded below.
```shell
dotnet add package MetaBrainz.MusicBrainz --version 5.0.0
dotnet add package MetaBrainz.MusicBrainz.CoverArt --version 5.0.0
```
