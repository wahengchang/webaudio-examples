# Audio Buffer
This is an example from : [https://developer.mozilla.org/en-US/docs/Web/API/AudioBuffer/getChannelData](https://developer.mozilla.org/en-US/docs/Web/API/AudioBuffer/getChannelData)


## Note 

#### `ArrayBuffer.getChannelData(channelIndex)`

It returns a `Float32Array` containing the PCM data associated with the channel, defined by the channel parameter (with 0 representing the first channel).


#### `ArrayBuffer.createBuffer()`

The createBuffer() method of the BaseAudioContext Interface is used to create a __**new, empty AudioBuffer object**__, which can then be populated by data, and played via an `AudioBufferSourceNode`

#### BaseAudioContext.createScriptProcessor()

It creates a ScriptProcessorNode used for direct audio processing.

`var scriptProcessor = audioCtx.createScriptProcessor(bufferSize, numberOfInputChannels, numberOfOutputChannels);`

## Reference
 - [https://developer.mozilla.org/en-US/docs/Web/API/AudioBuffer/getChannelData](https://developer.mozilla.org/en-US/docs/Web/API/AudioBuffer/getChannelData)