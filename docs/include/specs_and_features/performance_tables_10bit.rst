.. list-table:: Number of Real-Time Transcode Jobs (10-bit)
   :widths: 55 15 15 15
   :header-rows: 1

   * - Transcode Use Case
     - 1 Card
     - 2 Cards
     - 8 Cards
   * - 4kp60 *(HEVC decode)*
     - 2
     - 4
     - 16
   * - 4kp30
     - 4
     - 8
     - 32
   * - 1440p60
     - 4
     - 8
     - 32
   * - 1440p30 *(H264 decode)*
     - 8
     - 16
     - 64
   * - 1080p60
     - 6
     - 12
     - 48
   * - 1080p30
     - 16
     - 32
     - 128
   * - 720p60
     - 14
     - 28
     - 112
   * - 720p30
     - 28
     - 56
     - 224
   * - 540p60
     - 26
     - 52
     - 208
   * - 540p30
     - 46
     - 92
     - 368

.. list-table:: Number of Real-Time Transcode with Scale Jobs (10-bit)
   :widths: 55 15 15 15
   :header-rows: 1

   * - Transcode with Scale Use Case
     - 1 Card
     - 2 Cards
     - 8 Cards
   * - 4kp60 to 1440p60
     - 2
     - 4
     - 16
   * - 4kp30 to 1440p30
     - 4
     - 8
     - 32
   * - 1440p60 to 1080p60 
     - 4
     - 8
     - 32
   * - 1440p30 to 1080p30 *(H264 decode)*
     - 8
     - 16
     - 64
   * - 1080p60 to 720p60
     - 6
     - 12
     - 48
   * - 1080p30 to 720p30
     - 16
     - 32
     - 128
   * - 720p60 to 540p60
     - 14
     - 28
     - 112
   * - 720p30 to 540p30
     - 28
     - 56
     - 224
   * - 540p60 to 480p60
     - 26
     - 52
     - 208
   * - 540p30 to 480p30
     - 46
     - 92
     - 368

.. list-table:: Number of Real-Time ABR Ladders (10-bit)
   :widths: 55 15 15 15
   :header-rows: 1

   * - ABR Ladders Use Case
     - 1 Card
     - 2 Cards
     - 8 Cards
   * - 2160p60 to 2160p60, 1440p60, 1080p60, 720p30, 480p30, 360p30, 240p30, 144p30    *(HEVC only)*
     - 1
     - 2 
     - 8
   * - 2160p60 to 2160p60, 2160p30, 1440p30, 1080p30, 720p30, 480p30, 360p30, 240p30, 144p30    *(HEVC only)*
     - 1
     - 2
     - 8
   * - 2160p60 to 2160p60, 1440p30, 1080p30, 720p30, 480p30, 360p30, 240p30, 144p30    *(HEVC only)*
     - 1 
     - 2
     - 10
   * - 2160p60 to 2160p60, 1080p60, 720p60, 720p30, 480p30, 360p30, 160p30    *(HEVC only)*
     - 1
     - 2
     - 10
   * - 2160p60 to 2160p60, 720p60, 720p30, 480p30, 360p30, 160p30    *(HEVC only)*
     - 1
     - 2
     - 12
   * - 2160p60 to 1440p60, 1080p60, 720p30, 480p30, 360p30, 240p30, 144p30    *(HEVC only)*
     - 2
     - 4
     - 16
   * - 2160p30 to 2160p30, 1440p30, 1080p30, 720p30, 480p30, 360p30, 240p30, 144p30
     - 2
     - 4
     - 16
   * - 2160p30 to 1440p30, 1080p30, 720p30, 480p30, 360p30, 240p30, 144p30
     - 2
     - 4
     - 16
   * - 1440p60 to 1440p60, 1080p60, 720p30, 480p30, 360p30, 240p30, 144p30
     - 2
     - 4
     - 16
   * - 1440p60 to 1080p60, 720p30, 480p30, 360p30, 240p30, 144p30
     - 4
     - 8
     - 32
   * - 1080p60 to 1080p60, 720p60, 720p30, 480p30, 360p30, 160p30
     - 4
     - 8
     - 32
   * - 1080p60 to 720p60, 720p30, 480p30, 360p30, 160p30
     - 6
     - 12
     - 48
   * - 1080p30 to 1080p30, 720p30, 480p30, 240p30
     - 8
     - 16
     - 64
   * - 1080p30 to 720p30, 480p30, 360p30 
     - 14
     - 28
     - 112
   * - 720p30 to 720p30, 480p30, 240p30
     - 18
     - 36
     - 144
   * - 480p30 to 480p30, 240p30
     - 28
     - 56
     - 224

..
  ------------
  
  © Copyright 2020-2022 Xilinx, Inc.
  
  Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at
  
  http://www.apache.org/licenses/LICENSE-2.0
  
  Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.