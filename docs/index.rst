#######################################
|SDK|
#######################################

The |SDK| is a complete software stack allowing users to seamlessly leverage the hardware accelerated features of Xilinx video codec units and enable high-density real-time transcoding for live streaming video service providers, OEMs, and Content Delivery Network (CDNs). Included in the |SDK| are pre-compiled versions of FFmpeg and GStreamer which integrate video transcoding plug-ins for Xilinx devices, enabling simple hardware acceleration of video decoding, scaling and encoding using these popular tools. The |SDK| also provides a C-based application programming interface (API) which facilitates the integration of Xilinx video codec units transcoding capabilities in proprietary frameworks. The |SDK| can be leveraged on-premises with Alveo U30 cards and in the cloud with |VT1| instances.

|

.. note::
   A new Kubernetes plugin is available for U30 cards. This new plugin no longer requires an exact version number when specifying U30 resource limits. This allows for compatibility of pod description files across all releases of the |SDK|. Kubernetes clusters using this plugin will continue to work seamlessly even after an upgrade of the |SDK|. **If using Kubernetes, to prevent service degradation, it is necessary to deploy this new plugin (version 1.1.0)**  before upgrading to the latest version of the |SDK|. For more details, refer to the instructions for :ref:`deploying with Kubernetes <deploying-with-kubernetes>`. 

|

*************************
Quick Links
*************************

- :doc:`Specs and Features </specs_and_features>`
- :doc:`Release Notes </release_notes>`
- :doc:`Get Started on Premises with Alveo U30 </getting_started_on_prem>`
- :doc:`Get Started in the Cloud with Amazon EC2 VT1 </getting_started_on_vt1>`
- :doc:`Tutorials and Examples </examples>`

|

.. raw:: html

   <iframe 
     width="640" height="340"
     src="https://www.youtube.com/embed/kv-OS_cFOvg" 
     title="YouTube video player" 
     frameborder="0">
   </iframe>



.. toctree::
   :maxdepth: 3
   :caption: Get Started
   :hidden:

   Release Notes </release_notes>
   On Premises </getting_started_on_prem>
   Amazon EC2 VT1 </getting_started_on_vt1>
   Container Setup </container_setup> 
   Tutorials and Examples </examples>


.. toctree::
   :maxdepth: 3
   :caption: Reference Guides
   :hidden:

   Specs and Features </specs_and_features>
   Using FFmpeg </using_ffmpeg>   
   Using GStreamer </using_gstreamer>
   Tuning Quality of Encoded Video </tuning_encoding_quality>   
   Managing Compute Resources </managing_compute_resources>   
   Deploying with Kubernetes </deploying_with_kubernetes>
   C API Programming Guide </c_apis>   
   Card Management </card_management> 


.. toctree::
   :maxdepth: 3
   :caption: Support
   :hidden:

   File an issue <https://github.com/Xilinx/video-sdk/issues>
   Contributing </contributing> 
   Other versions <https://xilinx.github.io/video-sdk/browse.html>

..
  ------------
  
  © Copyright 2020-2022 Xilinx, Inc.
  
  Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at
  
  http://www.apache.org/licenses/LICENSE-2.0
  
  Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.