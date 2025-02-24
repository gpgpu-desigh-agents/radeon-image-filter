# Radeon Image Filter SDK

Harness the power of machine learning to enhance images with denoising, enabling your application to produce high quality images in a fraction of the time traditional denoising filters take.

Uses AMD’s MIOpen machine learning library, Microsoft® DirectML or Apple MPS for AI-accelerated denoising and upscaling
Also includes standard GPU-accelerated filters for rotation, blurring, tone mapping, color changes, anti-aliasing, and edge detection (the standard filters are not AI-accelerated)
Supports AMD GPUs as well as those of other vendors using OpenCL™ and DX12
Supports Apple® Metal®
Works across Windows®, Linux®, and macOS®

<div>
  <a href="https://github.com/GPGPU-Desigh-Agents/RadeonImageFilter/releases/latest/"><img src="http://gpuopen-librariesandsdks.github.io/media/latest-release-button.svg" alt="Latest release" title="Latest release"></a>
</div>

### Prerequisites
* Windows&reg; 7 (SP1 with the [Platform Update](https://msdn.microsoft.com/en-us/library/windows/desktop/jj863687.aspx)), Windows&reg; 8.1, or Windows&reg; 10
* Windows&reg; 10 19H1 or above for DirectML support
* Linux® Ubuntu 18.04, RHEL 7.x and 8.x and CentOS 7.x and 8.x
* macOS Mojave and Catalina

### Static Build
With release 1.6.1 we introduced static build too.
It is just for the main module, so RadeonImageFilters. The others ones will still be dynamic as we have a delay load mechanism for all of them.
Therefore in the Static folder you will only find the radeonImageFilters static lib/a file and the other dll/so/dylib file are located in the Dyniacm folder

### Documentation 
https://radeon-pro.github.io/RadeonProRenderDocs/rif/about.html
