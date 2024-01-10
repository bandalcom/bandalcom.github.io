---
layout: post
title:  "Postech KITA AI competition"
date:   2024-01-10 15:47:01 +0900
categories: AI CV CLUSTERING OCR
---

##  &nbsp;  

<!--
&nbsp; - space letter
img path = ~/bandalcom.github.io/posts_img/GitHub_Blog_Install/
img scale
small - width="40%" height="30%"
large - width="60%" height="40%"
-->
---  
  
When : 2023.07.07~2023.08.25  
Where : Offline  
Who : 29 people and 4 members (JS.Kwon, SY.Choi, SB.Choi, YJ.Han)  
What : A-Z about AI study  
Difficulty : 🔥🔥🔥🔥🔥  
관련 링크 첨부  
[https://newtradecampus.kita.net/page/user_job_AI_details](https://newtradecampus.kita.net/page/user_job_AI_details)  
[https://www.youtube.com/watch?v=e_7KcXoqalY&t=698s](https://www.youtube.com/watch?v=e_7KcXoqalY&t=698s)

---  

2023년 6월 18일 신청하여 대면 면접 진행 후,  
여름 방학 동안 오프라인으로 활동한 프로그램입니다.  
  
재학 3년 차 이상이고, 일정 수준 이상의 영어 점수가 지원 자격이었습니다.  
  
포항공대 인공지능연구원의 인턴십 지원 기회가 제공됐습니다.  
SK 디스커버리의 인턴 기회는 ~~있었는데~~ 없어졌습니다.  
  
교육 내용은 4주 간의 AI기술과, 3주 간의 AI비즈니스 전략 기획으로 나눠졌습니다.  
AI 기술 교육 내용으로는,  
파이썬 기초, 데이터 분석, 알고리즘, AI 리터러시, 머신러닝, 딥러닝, 언어 인공지능, AI 프로젝트가 있었습니다.  
  
AI 기술 교육 기간에는 월~금, 10시부터 5시까지 교육이 진행됐습니다.  
평균 12명 정도의 인원이 수업 이후 잔류하여 개인적으로 복습을 했습니다.  
5명 정도의 준~전공자들이 각 팀에 한명씩 분산되어 팀이 이뤄졌습니다.  
비전공자 교육생들이 해당 교육에 굉장히 어려움을 많이 겪었습니다.  
조금 과장하자면, 한 학기 인공지능 과정을 3일로 압축했습니다.  
압축된 5개의 인공지능에 대한 이론과 기술적인 내용을 3주 만에 소화하고  
남은 1주는 NLP 수업을 들으면서 프로젝트까지 진행하는  
정말 악독한 커리큘럼이 아닐 수 없습니다.  
  
개인적으로, "이걸 비전공자들이 따라올 수 있을까?"라는 생각이 매일 들었습니다.  
그럼에도 중도 포기자가 한명도 나오지 않은 상황에  
저는 정말 이 사람들은 뭐든 해내겠구나 싶었습니다.  
어떻게든 돕고 싶은 마음에  저도 알려줄 수 있는 개념은 최대한 공유해가며,  
대부분의 팀 프로젝트들에 다방면으로 도와준 기억이 납니다.  
  
생각나는 것들로는,  
사용 데이터의 볼륨과 프로젝트 접근 방향에 대한 내용,  
가상 환경과 GPU 사용에 대한 내용,  
웹크롤링 코드나 이미지 데이터 훈련 시에  
모델의 원리에 기반한 제가 생각하는 데이터 처리 방향성 등  
다양하게 피드백을 나누며 다 함께 성장할 수 있도록 솔직히 고생 좀 했습니다.  
  
일정을 소화하면서 병원도 가고 점점 피폐해져 가는 사람들을 보며 마음이 아프기도 했지만,  
열기를 잃지 않고 노력하신 분들에게 고맙고 정말 수고 많았다는 얘기를 하고 싶었습니다.  
덕분에 저도 똑같은 열기로 함께 개발하며 중요한 걸 배울 수 있었습니다.  
  
~~"굴리면 굴러가는 게 사람이구나!"~~  
"뭐든 하면 된다!"  
&nbsp;  
&nbsp;  

---
# Project Lecture AI  
  
저는 2조에서 프로젝트 총괄을 맡았습니다.  
주로 OCR 파트에서 Text Detection, Text Rearrange의 개발과  
Text Recognition의 보조를 수행하고,  
TTS 파트에서는 이슈 발생 시 코드 수정을 도왔습니다.  
전체적인 프로젝트의 관리와 개발 상황에 맞게 세부 조정을 진행했습니다.

&nbsp;  

프로젝트를 기획하게 된 배경은 제가 현실적으로 마주한 문제를 인식하고  
그 문제를 해결하고자 하는 시각에서 아이디어가 발생했습니다.  
다름 아닌 이 프로그램의 교육 과정이 진도가 굉장히 빠르고 어려우며  
내용이 상당히 많았기 때문에 생긴 문제였습니다. 
교수님의 판서와 ppt 내용을 필기하고 있으면  
교수님이 따로 언급하시는 내용을 놓쳐서 수업 내용에 대한 습득 효율이 떨어지고,  
교수님의 발화에 집중하며 수업 자체에 집중하면  
학습 효과는 좋지만 수업 이후에 복습하기 위한 자료가 빈약하여 어려움을 느꼈습니다.  
*요약하자면 수업 따라가기 벅차서 자동 노트 필기 AI 개발하고 싶었습니다.  

&nbsp;  

이 서비스의 개발을 통해 창출하고 싶었던 가치는  
수강자들이 서비스 이용으로 필기에 대한 압박감에서 벗어나고  
교수자와 온전한 상호작용을 통해 수업의 질적 향상을 구상했습니다.  
장애인 수강 보조 서비스로의 확장 가능성 또한  
유의미한 사회적 가치 실현이라고 판단하여  
주제를 최종 선정하고 개발하게 되었습니다.  
  
&nbsp;  
  
프로세스는 다음과 같이 디자인했습니다.  
{% include ProcessFlowchart.html %}  
  
&nbsp;  
  
효율적인 개발을 위해 프로젝트는 OCR과 TTS 파트로 나누었습니다.  
OCR 파트에 2명, TTS 파트에 3명의 인원을 배정했습니다.  
OCR 파트에서는 제가 Text Detection, Text Rearrange의 구현을 맡았고,  
다른 OCR 파트원 YJ.Han이 Text Recognition을 담당하였습니다.  
TTS 파트에서는 JS.Kwon, SY.Choi, SB.Choi 세 팀원들이 Voice Recognition의 개발을 맡았습니다.  
TTS 파트는 저도 아직 모르는 부분이 많기 때문에 설명에서 생략하도록 하겠습니다.  
&nbsp;  
&nbsp;  

---

# Text Detection Model 개발  
  
## Data preprocess  
Dataset : [IAM handwriting dataset](https://paperswithcode.com/dataset/iam)  
  
<img src="/posts_img/Postech&KITA_AI_program/CharacterLabelingExample.jpg" width="40%" height="30%" title="BANDALCOM" alt="CharacterLabelingExample.jpg">  
위처럼 Character 각각에 BBox labeling되어있는 IAM handwritting dataset을  
  
<img src="/posts_img/Postech&KITA_AI_program/WordLabelingExample.jpg" width="40%" height="30%" title="BANDALCOM" alt="WordLabelingExample.jpg">  
다음과 같이 word 별로 labeling이 되도록 함과 동시에  
coco format의 BBox Label을 Yolo format으로 변환하는 코드 구상  
=> convertxml2yolo.ipynb  
&nbsp;  
&nbsp;  

## Model train  
yolov5s pretrained model을 가져와  
전처리를 마친 IAM handwritting dataset으로  
word image detection model 훈련  
&nbsp;  
&nbsp;  

## Model test  
훈련 모델 테스트  
<img src="/posts_img/Postech&KITA_AI_program/hyj_paper_text_detection_result.jpg" width="40%" height="30%" title="BANDALCOM" alt="hyj_paper_text_detection_result.jpg">  
꽤 잘 나옵니다.  
사실 위의 이미지를 사용하진 않고  
단어 이미지를 text recognition model에 넘겨야 하기 때문에  
crop option을 사용하여 cropped image들을 추출해줍니다.  
&nbsp;  
&nbsp;  

image detection을 통해 handwritten text image에서  
각각의 word image를 추출했으나,  
순서를 알지 못하게 단어만 확인이 되어  
원래 글의 의미를 잃어버리는 문제가 있었습니다.  
다만 추출 시에 단어의 좌표값을 포함시킬 수 있었기에  
각 단어의 이름에 x,y좌표값과 w,h 정보를 포함하여  
단어 이미지 파일을 생성합니다.  
  
각 단어 이미지들의 raw img data에서 위치 관계를 알기 위해,  
crop image 생성 전에 좌표 데이터 후 처리하여  
이미지 파일명에 라벨링하는 코드를 detect.py에 추가했습니다.  
<img src="/posts_img/Postech&KITA_AI_program/DetectFileFix.jpg" width="60%" height="40%" title="BANDALCOM" alt="DetectFileFix.jpg">  
  
<img src="/posts_img/Postech&KITA_AI_program/XYWHcroppedImg.jpg" width="60%" height="40%" title="BANDALCOM" alt="XYWHcroppedImg.jpg">  
&nbsp;  
&nbsp;  

---
  
# Text Rearrange Process 개발  
  
yolo model을 통해 crop된 이미지들은  
파일 이름에 crop되기 전 raw image에서의 좌표 정보를 포함합니다.  
Example>  
x89y147w199h184.jpg  
x10y148w157h184.jpg  
x28y149w108h180.jpg  
  
raw image파일에서 같은 line에 있던 word들은  
가까운 y값을 갖고있을 것이므로,  
밀도기반 군집화 알고리즘을 사용하여  
같은 line에 있을 것이라고 예상하는 word값들은  
동일 클러스터에 속하게 됩니다..  
이렇게 동일 클러스터에 속하는 y값들의 평균을 구하여  
word의 새로운 y값으로 label.  
단어 이미지 파일 rename할 때, y값이 먼저 오게 합니다.  
Example>  
yyyy_xxxx.jpg  
  
y값에 대한 정렬이 되고  
x값에 대해 오름차순으로 정렬됩니다.  
Example>  
0148_0010.jpg  
0148_0028.jpg  
0148_0089.jpg  
  
word file의 순서가 자동적으로 원래 text의 의미를 가지게 됩니다.  
<img src="/posts_img/Postech&KITA_AI_program/DBSCANchange.jpg" width="40%" height="30%" title="BANDALCOM" alt="DBSCANchange.jpg">  
&nbsp;  

---
  
# Text Recognition Model 개발  
## Data collection & preprocess  
Text Detection에서 사용했던 IAM dataset을 재활용했습니다.  
raw image data의 각 단어에 대한 텍스트 라벨링이 있었습니다.  
훈련된 Text detection model을 사용해  
단어 이미지들을 추출하고 해당 텍스트 라벨과 매칭시킵니다.  
word image에 대한 word text로 이루어진 새로운 dataset을 구축했습니다.  
해당 dataset을 IAM.m2이라고 해두겠습니다.  
- IAM.m2 dataset - 115,320 words  
&nbsp;  

그리고 서비스 기획에 따라 두 가지 모델을 훈련해야 하기 때문에  
YJ.Han 팀원이 가지고 있던 영문 필기 노트를 전처리 작업 후  
Text Detection model로 1000여개 단어 이미지 추출했습니다.  
SY.Choi 팀원은 영문 필기 노트가 없어  
문학 작품 필사로 2000개 단어 작성 후 동일하게 image crop했습니다.  
라벨링 업무 프로세스의 효율성을 위해 자체 라벨링 프로그램 개발 후,  
두 팀원 YJ.Han, SY.Choi에게 전달하여 각 단어 이미지에 대한 라벨링을 수행했습니다.  
=>LabelingCode.ipynb  
  
최종적으로 서로 다른 필체의 두 가지 dataset을 구축 완료했습니다.  
- HYJ dataset - 1,179 words  
- CSY dataset - 2,072 words  

&nbsp;  
&nbsp;  

## Model training and test  
Naver Clover의 text recognition model을 가져와 전이학습을 진행했습니다.  
Scene Text Recognition 모델을 선택한 이유는  
실생활에서 보이는 불규칙한 text 이미지에 인식에 초점을 두고 개발된 만큼  
악필, 노이즈가 많은 판서, 필기 데이터에도 강건한 성능을 보여줄 것으로 생각함.  
&nbsp;  

### First Transfer Learning with IAM.m2 dataset  
pretrained model을 불러와서 IAM.m2 dataset으로 transfer learning을 진행  
<img src="/posts_img/Postech&KITA_AI_program/IAM.m2_Dataset.jpg" width="40%" height="30%" title="BANDALCOM" alt="IAM.m2_Dataset.jpg">  
IAM TextRecognition model  
accuracy : 83.531  
valid loss : 0.60929  
&nbsp;  

### Second Transfer Learning with HYJ dataset  
transfer learning한 IAM TextRecognition model을 불러와서,  
{HYJ dataset}으로 다시 transfer learning을 진행  
<img src="/posts_img/Postech&KITA_AI_program/HYJ_Dataset.jpg" width="40%" height="30%" title="BANDALCOM" alt="HYJ_Dataset.jpg">  
IAM-HYJ TextRecognition model  
accuracy : 92.792  
valid loss : 0.36510  
&nbsp;  

### Second Transfer Learning with CSY dataset  
transfer learning한 IAM TextRecognition model을 불러와서,  
{CSY dataset}으로 다시 transfer learning을 진행  
<img src="/posts_img/Postech&KITA_AI_program/CSY_dataset.jpg" width="40%" height="30%" title="BANDALCOM" alt="CSY_dataset.jpg">  
IAM-CSY TextRecognition model  
accuracy : 91.220  
valid loss : 0.27884  
  
다양한 필기체를 가진 IAM으로 초벌 훈련하고,  
이후 단일 필기체에 대한 (HYJ/CSY) dataset으로 재벌 훈련을 수행한 결과,  
accuracy가 많이 향상된 것을 확인할 수 있었습니다.  
서로 다른 필기체로 모델을 각각 훈련하여,  
동일 글씨체에 대하여 더 좋은 성능을 이끌어낼 수 있었고,  
이는 개인-최적화된 모델 개발에 의의가 있었습니다.  
  
추후 개발 가능성:  
강사 얼굴 인식을 통한 판서 모델 스위칭.  
게임 형식으로 필요한 수업 내용만 Popup시켜서  
학습자가 원하는 정보만 가져갈 수 있도록 개발.  
혼합어, 기호, 도형 등의  dataset에 대한 추가 훈련을 통해  
더 풍부한 학습 지원이 가능하도록 개선.  
소형 단말 기기를 통해 실시간으로 강의 영상을 전달 받아서  
처리 후 전달하는 프로세스 추가.  
&nbsp;  
&nbsp;  

---
  
7월부터 8월까지 두달간의 굉장히 intensive한 대외활동이었습니다...  
이 활동 이후에는 꽤 하드한 일정이라도 별 탈 없이 소화할 수 있습니다.  
  
엘리트 대학생 인공지능 전략과정(a.k.a 엘대인전)  
엘대인전 1기로 수료를 했습니다.  
파일럿 프로그램이었던 만큼 다양한 우여곡절이 있었는데요,  
엘대인전 2기는 없다는 결과가 많은 것을 설명해 주는 듯 합니다.  
나쁜 의미에서 2기가 없는 게 아니라  
너무 고급 인적 리소스가 많이 들어가는 프로그램이다 보니  
2024년에는 대학생 인공지능 무역캠프라는 프로그램으로  
개편할 수 밖에 없었다고 봅니다.  
사실 처음 시작부터 담당자께서  
프로그램이 1기로 마무리할 수도 있다는 얘기를 하셔서  
어느 정도 예상된 결과였습니다.  
  
정말 좋은 강의를 해주신 윤은영 교수님, 유환조 교수님, 안희갑 교수님, 최승진 교수님, 유환조 교수님 감사드립니다.  
AI전략 기간에 특강을 해주신 김영롱님, 윤성의님, SK discovery C&C의 AI팀원분들께  
알찬 내용의 강의 해주셔서 감사하다는 말을 전하고 싶습니다.  
&nbsp;  
&nbsp;  

---
  
3학년 2학기 종강 이후에 개인적으로 다시 코드를 뜯어보며 정리를 했습니다.  
코드 짜는 것보다 코드 보는 게 더 중요하다는 얘기를 얼핏 들었는데요.  
재미없는 걸 보니 중요한 게 확실합니다.  
  
Lecture AI에서 TTS 파트를 제외하고  
OCR 파트 프로세스를 app으로 배포해봤습니다.  
  
Huggingface GRADIO space에 올라간 Note Crawling AI app의 Flowchart  
{% include NoteCrawlingFlowchart.html %}  
&nbsp;  
&nbsp;  
한번 사용해보세요.  
손글씨 이미지가 아니더라도 영문 텍스트 이미지면 가능합니다.  
  
<script
type="module"
src="https://gradio.s3-us-west-2.amazonaws.com/4.13.0/gradio.js">
</script>  
  
<gradio-app src="https://nebulae000-notecrawling.hf.space"></gradio-app>  
  
[huggingface NoteCrawling](https://huggingface.co/spaces/Nebulae000/NoteCrawling)


Thank you for reading!

---

BANDALCOM🐻