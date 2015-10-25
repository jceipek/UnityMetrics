# UnityLogger

## Usage:

1. Move the `Logger` folder into your project.
2. Add logging to your scripts:

```
// At the top of a script that needs logging
using Giverspace;


//....
// somewhere where you need to log a position and orientation:
	Log.Metrics.PlayerPosRotMessage(transform.position, transform.forward);
//....

//....
// somewhere where you need to log a string:
	Log.Metrics.Message("Here's a string message example!");
//....
```

3. Add additional logging formats by modifying the sections of `Logging/Logger.cs` that indicate `TODO:`

## License: MIT