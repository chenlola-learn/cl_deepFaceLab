# Introduction

|Key Points|info|
|---|---|
| Required Hardware | |
| terminology | Frames; Dataset; Model; Video|
| A Good deepfake requires| source and target person have similarly shaped head | 
| new AMP model | promises to address the issue of diffrent face shapes a bit it's still imporant|


| 1.Workspace cleanup/deletion: | info |
|---|---|
|[Clear Workspace]| deletes all data from the "workspace" folder |


| 2. Frames extraction from source video | info |
|---|---|
| a) Extract each video separately| *2)Extract images from video data_src*  |
| b) editing in Video editing software ||
| c) alternative method: MVE||
|png vs jpg| Png > Jpg |


|3. Frames extraction from destination video (data_dst.mp4) |info|
|---|---|
|3) extract images from video data_dst FULL FPS||



| 4. Data_src faces extraction/alignment: |info|
|---|---|
|4) data_src faceset extract| use this first|
|-----  Face Type ||
|----------  a) Full Face/FF | not recommended as it limits you to FF area of coverage|
|----------  b) Whole Face/WF | recommended as an universal/futureproof solution
|----------  c) Head - for HEAD models | requires very high resolution extraction|
|----- Max number of faces from image | how many faces extractor should extract from frame.|
|----- Resolution of the dataset | read more: : https://mrdeepfakes.com/forums/thread-gu...9#pid18459|
|-----Jpeg quality | DFL can only extract face in JPG format.|
|----- Choosing whether to generate "aligned_debug" images or not |  used to check if landmarks are correct however this can be done with MVE  |

| 4. Data_src cleanup |info|
|---|---|
|clean the SRC dataset of false positives and incorrectly aligned faces||
|2|3|