# APIs and rust libraries

Selection of possible video coding APIs.  
FFmpeg is excluded because of problems with compilation and licenses.

## Encode

* x264: [x264](https://github.com/quadrupleslap/x264) (old, high level bindings)
* VAAPI: [libva-sys](https://github.com/vgarleanu/libva-sys) (new, raw bindings)
* AMF: [amf-rs](https://github.com/legion-labs/amf-rs) (new, high level bindings, not on crates.io)
* NVENC: none available (create bindings)
* VK_EXT_video_encode_h264: [ash](https://github.com/MaikKlein/ash)
* MFT: [winapi](https://github.com/retep998/winapi-rs)

## Decode

* Mediacodec: [ndk-sys](https://github.com/rust-windowing/android-ndk-rs) (raw bindings)
* VK_EXT_video_decode_h264, VK_EXT_video_decode_h265: [ash](https://github.com/MaikKlein/ash)
