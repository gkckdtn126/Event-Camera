# Event-Camera Project
### 1. event camera로부터 depth을 뽑아오고,  depth를 뽑은 데이터를 활용해서 pseudo lidar algorithm에 넣어서 lidar data를 가져와서 lidar data를 이용해서 3d yolo에 적용하는 방법, 
### 2. orin kit랑 event cmaera와 터틀봇(scout mini)를 이용해서 event camera로 자율주행(frame + event) + stereo camera까지? stereo camera로부터 받은 depth를 event camera로 뽑은 depth와 비교해서 event camera로 뽑은 depth를 발전시킨다? 
### pseudo lidar에 필요한 것: depth map, stereo calibration file!, event camera로 stereo calibration file을 어케 만드냐? 
### carla를 이용해서 stereo event camera로 depth map 뽑아낸다 -> depth map 만든다 -> camera calibration을 한다. camera calibration을 한 후에, 이 파일을 event camera로 만든 depth map이랑 합쳐서 pseudo lidar에 넣어준다? 
### 필요한거? event camera dataset, calibration file, rgb image, depth map, 
### image를 event dataset으로 바꾸는 작업이 있을까
### https://dsec.ifi.uzh.ch/dsec-datasets/download/ 여기서 데이터셋 이용하고, disparity 뽑는 알고리즘으로 disparity 뽑아보자, pseudo lidar training을 한번 더 시켜야 하는것인가????????????????????????이건 나중에!
