Encoder mpsoc_vcu_hevc [MPSOC VCU HEVC Encoder]:
    General capabilities: delay threads avoidprobe 
    Threading capabilities: auto
    Supported pixel formats: xlnx_xvbm nv12
MPSOC VCU HEVC encoder AVOptions:
  -control-rate      <int>        E..V..... Rate Control Mode (from 0 to 3) (default cbr)
     const-qp                     E..V..... Constant QP
     cbr                          E..V..... Constant Bitrate
     vbr                          E..V..... Variable Bitrate
     low-latency                  E..V..... Low Latency
  -max-bitrate       <int64>      E..V..... Maximum Bit Rate (from 0 to 3.5e+10) (default 5e+06)
  -slice-qp          <int>        E..V..... Slice QP (from -1 to 51) (default auto)
     auto                         E..V..... Auto
  -min-qp            <int>        E..V..... Minimum QP value allowed for the rate control (from 0 to 51) (default 0)
  -max-qp            <int>        E..V..... Maximum QP value allowed for the rate control (from 0 to 51) (default 51)
  -bf                <int>        E..V..... Number of B-frames (from 0 to UINT32_MAX) (default 2)
  -periodicity-idr   <int>        E..V..... IDR Picture Frequency (from -1 to UINT32_MAX) (default -1)
  -profile           <int>        E..V..... Set the encoding profile (from 0 to 1) (default main)
     main                         E..V..... Main profile
     main-intra                   E..V..... Main Intra profile
  -level             <int>        E..V..... Set the encoding level restriction (from 10 to 51) (default 1)
     1                            E..V..... 1 level
     2                            E..V..... 2 level
     2.1                          E..V..... 2.1 level
     3                            E..V..... 3 level
     3.1                          E..V..... 3.1 level
     4                            E..V..... 4 level
     4.1                          E..V..... 4.1 level
     5                            E..V..... 5 level
     5.1                          E..V..... 5.1 level
  -tier              <int>        E..V..... Set the encoding tier (from 0 to 1) (default main)
     main                         E..V..... Main tier
     high                         E..V..... High tier
  -slices            <int>        E..V..... Number of Slices (from 1 to 68) (default 1)
  -qp-mode           <int>        E..V..... QP Control Mode (from 0 to 2) (default auto)
     uniform                      E..V..... Use the same QP for all coding units of the frame
     auto                         E..V..... Let the VCU encoder change the QP for each coding unit according to its content
     relative-load                E..V..... Use the information gathered in the lookahead to calculate the best QP
  -aspect-ratio      <int>        E..V..... Aspect-Ratio (from 0 to 3) (default auto)
     auto                         E..V..... 4:3 for SD video, 16:9 for HD video, unspecified for unknown format
     4:3                          E..V..... 4:3 aspect ratio
     16:9                         E..V..... 16:9 aspect ratio
     none                         E..V..... Aspect ratio information is not present in the stream
  -scaling-list      <int>        E..V..... Scaling List Mode (from 0 to 1) (default default)
     flat                         E..V..... Flat scaling list mode
     default                      E..V..... Default scaling list mode
  -cores             <int>        E..V..... Number of cores to use (from 0 to 4) (default auto)
     auto                         E..V..... Automatic
  -lookahead_depth   <int>        E..V..... Number of frames to lookahead for qp maps generation or custom rate control. Up to 20 (from 0 to 20) (default 0)
  -temporal-aq       <int>        E..V..... Enable Temporal AQ. (from 0 to 1) (default enable)
     disable                      E..V..... Disable Temporal AQ
     enable                       E..V..... Enable Temporal AQ
  -spatial-aq        <int>        E..V..... Enable Spatial AQ. (from 0 to 1) (default enable)
     disable                      E..V..... Disable Spatial AQ
     enable                       E..V..... Enable Spatial AQ
  -spatial-aq-gain   <int>        E..V..... Percentage of spatial AQ gain (from 0 to 100) (default 50)
  -latency_logging   <int>        E..V..... Log latency information to syslog (from 0 to 1) (default 0)
  -expert-options    <string>     E..V..... Expert options for MPSoC HEVC Encoder
  -tune-metrics      <int>        E..V..... Tunes MPSoC HEVC Encoder's video quality for objective metrics (from 0 to 1) (default disable)
     disable                      E..V..... Disable tune metrics
     enable                       E..V..... Enable tune metrics

