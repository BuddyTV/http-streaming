## HTTP-Streaming (BuddyTV)

### Introduction
This library was forked from the original [video.js http-streaming](https://github.com/videojs/http-streaming) library, in order to provide a workaround for an **Ad Stuttering** issue that was detected.

### Configuration
This feature can be configured when the VideoJS player is initialized using the following options:
```
html5: {
  vhs: {
    nudgeOffset: 0.2, // seconds to nudge
    enableNudgeOnError: this.nudgeOffset !== 0 // enable if not zero
  }
}
```

Set nudgeOffset to 0, to disable the feature

### Getting Started
In order to get started with this project, please refer to the original instructions on the [http-streaming](https://github.com/videojs/http-streaming) page.

### Publishing
This is published on the public npm repo, under the name **[http-streaming-buddytv](https://www.npmjs.com/package/http-streaming-buddytv)**.

For permissions to deploy this library, please contact the owner *Phineas Kibbey*.