---
layout: post
title:  "Data AI Hackathon Project"
date:   2023-12-31 16:28:01 +0900
categories: AI NLP
---
  
##  &nbsp;  


<!--
&nbsp; - space letter
img path = ~/bandalcom.github.io/posts_img/CJ_Hackathon/
img scale
small - width="40%" height="30%"
large - width="60%" height="40%"
-->
---
  
&nbsp;  
---  
# Chapters  
## [0. Introduction](#introduction)  
## [1. Weekly Task Review](#weekly-task-review)  
## [2. Presentation Review](#presentation-review)  
## [3. Hackathon Review](#hackathon-review)  
  
&nbsp;  
  
---
## Introduction  
  
&nbsp;  
   
<img src="/posts_img/CJ_Hackathon/crush_on_ai_post.jpg" width="60%" height="40%" title="BANDALCOM" alt="crush_on_ai_post.jpg">  
<img src="/posts_img/CJ_Hackathon/Hackathon_sumittion_info.jpg" width="60%" height="40%" title="BANDALCOM" alt="Hackathon_sumittion_info.jpg">  
  
&nbsp;  
  
| Receiving Period | 2023.08.30 ~ 2023.10.13 23:59 |  
| -------- | -------------------------------------- |  
| Training Period | 2023.10.16 to 2023.11.10 |  
| Training hours | Monday to Sunday (18:00 to 23:00), Total 160 hours (8 hours/day)<br>Live Online Lectures |
  
&nbsp;  
  
{Crush On AI}  
Data & AI 3rd Program with CJ OliveNetworks  
AI Hackathon project  
  
&nbsp;  
  
When : 2023.10.16~2023.11.10  
Where : Online  
Who : +5 members (SR.Lee, HJ.Kang, SH.Jeon, ML.Heo, CM.Lee)  
What : Natural Language Processing Based Artificial Intelligence Project  
Difficulty : 🔥🔥🔥🔥  
Website Link [🌠](https://digital.eksa.or.kr/portal/ict/coursedetail_digital_3.user?paramMap.type=1)  
  
&nbsp;  
  
This article was written about the activities of participating in the 3rd Data & AI Hackathon Project organized by CJ OliveNetworks for 4 weeks from mid-October to early November.  
  
&nbsp;  
  
---
## Weekly Task Review  
  
&nbsp;  
  
As it was a process of experiencing the overall practical processes, there were activities such as scrum, mentoring office hour, planning, and reporting.  
  
&nbsp;  
  
| Classified | lecture topics                       | lecture contents                                                                               |
| ---------- | ------------------------------------ | ---------------------------------------------------------------------------------------------- |
| Week 1     | Guided Project                       | Guidelines and Lectures to prepare for the project<br>Group meetings and data analysis             |
| Week 2     | data research/analysis and planning  | Selection of topics through Ideation based on the latest trend research<br><br>1st draft of the plan |
| Week 3     | Production of Prototype and Plan Complementation | Create Prototype (model discovery and service design)<br>Second revision and supplementation of the plan                       |
| Week 4     | Organize and present the results.                    | Check the progress of the project<br>Announcement of project outcomes                                               |
  
&nbsp;  
  
---  
## Week 1  
SKIP  
  
&nbsp;  
  
---
## Week 2  
### Explore and select topics, models, and data  
#### Theme Keywords  
Voice phishing, real estate, lunch,  
coffee, books, review analysis,  
spam texts, trend analysis, bibliographic data,  
click-bait, career paths  
  
&nbsp;  
  
#### Preliminary Topic Selection  
**Click-bait Classification - 5 votes**  
**Data summary and organization service - 4 votes**  
**Social Media keyword-based sentimental analysis - 4 votes**  
Coffee Type-Based Recommendation System - 2 votes  
Voice Phishing, Smishing Related Categories - 1 Vote  
Popular Library Book-Based Market Response Forecast - 1 Vote  
Analysis of reviews between specific products (Galaxy vs. iPhone)  
Interview text-based differentiation analysis  
Forecast of fluctuation rate based on previous day's article analysis  
Career classification based on student career counseling  
  
&nbsp;  
  
#### Final Topic Selection  
<img src="/posts_img/CJ_Hackathon/final_top.jpg" width="40%" height="30%" title="BANDALCOM" alt="final_top.jpg">  
Each of us came up with at least one topic,  
did an idea briefing at the meeting, and selected three preliminary topics.  
We conducted further research on three preliminary topics and shared the contents of each topic.  
As the final topic for Hackathon,  
our team chose the Click-bait Classification Service,  
which received four votes in the final vote.  
The reason for the drop in document management topics is that there is not much to show compared to the other two topics.  
The reason why SNS analysis received a small number of votes was that it was questioned whether it would be possible to build a dataset in a limited time.  
The classification of click-bait was selected because the dataset was ready to use compared to the two topics.  
It was considered novel idea among these topics.  
  
&nbsp;  
  
---  
### 프로젝트 기획  
#### 조 구성원  
**조 이름**: 낭만어부  
**조장**: BANDALCOM  
**조원**: SR.Lee, HJ.Kang, SH.Jeon, ML.Heo, CM.Lee  

&nbsp;  

#### 프로젝트 개요  
**프로젝트 명**: 
낭만어부의 낚시 기사 여부 및 유형 판별 서비스, 'PressPulse'  

&nbsp;  

**프로젝트 주제**:  
낚시 기사 여부와 그 기사의 유형을 분류하는 판별 시스템을 정립한다.  
더 나아가 기사 URL 입력 시 낚시 기사 여부와 그 유형을 판별하는 App 혹은 Web을 구성한다.  

&nbsp;  

**주제 선정 배경**:  
저널리즘학의 대부, 빌 코바치에 따르면 저널리즘은 ‘진실성’이라는 중요한 의무를 지닌다.  
하지만 최근 기사들은 조회수를 높이기 위해 자극적이거나 오해의 소지가 있는 기사 제목을 사용하는 경향이 있다.  
이런 사회 현상 속에서 독자들은 기사를 비판적인 시각으로 받아들여야 한다는 경각심을 일깨워야 할 필요가 있다.  
‘진실성’이 결여된 기사, 즉 낚시성 기사(click-bait)가 가져오는 빈번한 사회 문제로 인해 자연어 처리로 이를 분별하려는 노력은 2018년부터 이루어졌다.  
(참고 기사: [https://www.joongang.co.kr/article/22600687#home](https://www.joongang.co.kr/article/22600687#home))|
&nbsp;  
현재에는 대규모 언어모델을 통해 감정 키워드를 분류할 수 있다는 점에 착안해,  
낚시성 기사 판별에 유형 분류 서비스까지 제공하는 새로운 방안을 마련하고자 한다.  

&nbsp;  

**프로젝트 요약**:  
1. 한국어 기반 대규모 언어모델 학습을 통해 기존 모델과의 성능을 비교한다.  
2. 낚시성 기사는 총 10개의 유형으로 분류한다.  
3. ‘LangChain’을 활용해 모델을 배포하며, 구현 가능한 서비스로 확장한다.  

&nbsp;  

**목표 인사이트**:  
{기술적 측면}  
• 대규모 언어 학습에 대해 이해하고, 활용 방안을 탐색한다.  
• 모델 학습에 이은 모델 배포 파이프라인을 구성한다.  
{서비스 측면}  
• 언론사에 단순히 클릭만을 위한 기사가 쏟아지는 사회 문제와 ‘진실성’ 의무에 대한 경각심을 심어준다.  
• 독자에게 비판적인 시각으로 기사를 봐야 한다는 경각심을 심어준다.  

&nbsp;  

**차별 요소**:  
{연구적 측면 – Data-Centric Perspective}  
현재 인공지능 모델들은 하이엔드라고 생각될 만큼 상향 평준화되어 있다.  
이런 상황 속에서 이제는 ‘Model-Centric’ 관점에서 벗어난 ‘Data-Centric’ 관점에서 데이터를 이해해 성능을 개선해야 한다.  
(참고 강의:  [https://www.youtube.com/watch?v=06-AZXmwHjo](https://www.youtube.com/watch?v=06-AZXmwHjo))<br>  
따라서 이번 프로젝트에서는 모델의 Hyperparameter는 고정하고,  
데이터를 다양하게 변경하며 접근해 ‘특정 목적으로 생성된 데이터로 훈련할 경우,  
현실의 데이터를 잘 설명할 수 있는가?’를 검증하고자 한다.  
모델 설명력보다 데이터의 설명력에 중점을 둬 고민한다는 것이다.<br>  

&nbsp;  

{서비스 측면 - 기업과 사용자 입장에서}  
• 사용자(독자)  
낚시 기사 여부만을 판별하는 기존 서비스와 달리 낚시 기사의 유형을 분류하는 방향으로 확장해 소비자에게 클릭 선택권을 부여한다.  
이에 더해 LangChain과 Gradio를 활용해 유저 친화적인 UI 서비스를 구성하여 사용자들이 쉽게 접근할 수 있도록 한다.  
이로써 기사를 보는 비판적인 시각인 ‘미디어리터러시’ 능력을 증진함으로써 거짓된 기사를 스스로 판별할 수 있다.<br>  
• 기업(언론사와 기자)  
언론사는 저널리즘의 ‘진실성’ 의무에 대한 주의를 기울일 수 있다.  
그리고 기자는 기사 작성 과정에서 오해의 소지가 될 수 있는 요소가 들어가지 않았는지 확인하며 퇴고할 수 있다.<br>  

&nbsp;  

#### 활용 데이터 셋  
낚시성 기사 탐지 데이터  
[AI-Hub (aihub.or.kr)](https://aihub.or.kr/aihubdata/data/list.do?searchKeyword=%EB%82%9A%EC%8B%9C%EC%84%B1+%EA%B8%B0%EC%82%AC)
  
&nbsp;  
  
#### 진행 계획  
  
| 일정                | 내용                       | 역할                   |
| ------------------- | -------------------------- | ---------------------- |
| 23.10.25 ~ 23.11.03 | 데이터 전처리 및 모델 학습 | DC.Ban, SR.Lee, HJ.Kang |
| 23.11.04 ~ 23.11.10 | 모델 성능 비교 및 배포     | CM.Lee, SH.Jeon, ML.Heo |
  
&nbsp;  
&nbsp;  
  
---  
## Week 3  
### Data Preprocessing  
Feature Selection:  
newTitle(기사 제목), newsContent(기사 본문), useType(용도 유형), processPattern(처리 패턴)  
Label Decoding:  
Decode "processPattern(Encoded, Categorical)" into string type  

&nbsp;  

1. ~~sampling 5% from each original data~~
2. Data Sampling: 1000 samples from each processPattern  
3. Text data Cleaning  
4. Prompt modify (Instruction Extension + α)  
  
&nbsp;  
  
|Sort|text|
|---|---|
|Pre-Instruction (string)|판별은 입력의 기사제목과 기사내용을 분석하여 해당 기사의 낚시성 기사 또는 정상기사, 낚시기사 유형을 출력합니다.<br><br>다음은 기사 제목, 기사 내용를 제공하는 입력과 짝을 이루는 판별 작업을 명령하는 지침입니다.<br><br>요청을 적절하게 완료하는 응답을 작성합니다.|
|Instruction (string)|주어진 기사를 읽고 낚시성 기사 유무를 판별하라|
|Input (string)|기사제목: f\"내 통장에 웬 15억\"…오송금 된 돈으로 호화생활 30대男의 최후<br><br>기사내용: f은행 실수로 하루아침에 백만장자가 된 남성이 징역 6년을 선고받아 억울함을 호소했다. 최근 뉴스위크는 지난해 6월 러시아 툴라에 있는 ATM에서 돈을 인출하는 과정에서 통장에 9520만 루블(약 14억 6700만원)을 발견한 남성의 사연을 보도했다. … (후략)|
|Output (string)|해당기사는 낚시성기사입니다. 낚시기사 유형은 의문 유발형(부호) 입니다.|
  
&nbsp;  
  
### Model Training  
**Model selection**  
LLaMa2 7B  
Polyglot ko 1.3B, 5.8B, 12.8B  
==Final model : Polyglot ko 1.3B==  
Polyglot ko 1.3B is a sLLM Model  
  
&nbsp;  
  
### Model Test  
**Minimum Loss : 1.6**  
#### Generation Problem Occurrence  
What we expected for the output text was like this below.  
"해당기사는 {Click-bait T/F}입니다. 낚시기사 유형은 {Click-bait pattern}입니다."  
However, Text Generation didnt give us an answer in perfect form.  
When we had only gave a text prompt of Instructions and Input,  
model just generated some more article text after the input.  
Therefore, I put one more keyword at the end of the text prompt - "해당기사는"  
I put this keyword on purpose to let model generate a text based on the dataset it learned.  
Since the generative model is a mechanism that generates the most likely word after a particular word,  
I thought that if the model had learned the dataset well,  
it would also have learned the tendency of which words come out after the keyword "해당기사는".  
Wrong Text Generation Problem Solved✅  
  
&nbsp;  
  
### Model Deploy  
Gradio : Chatbot UI  
Langchain : LLM model pipeline  
<img src="/posts_img/CJ_Hackathon/gradio.jpg" width="40%" height="30%" title="BANDALCOM" alt="gradio.jpg">  
<img src="/posts_img/CJ_Hackathon/langchain.jpg" width="40%" height="30%" title="BANDALCOM" alt="langchain.jpg">  
  
&nbsp;  
&nbsp;  
  
---  
  
## Week 4  
### Presentation 
Location : Twin City 10F, 366, Hangang-daero, Yongsan-gu, Seoul, Republic of Korea (CJ OLIVENETWORKS OFFICE)  
  
&nbsp;  
  
---
  
&nbsp;  
&nbsp;  
  
  
  
## Presentation Review  
---  
### 심사 평가 기준  
창의성(20)  
- 새로운 가치를 제공하거나 기존 문제를 해결하는가?  
- 차별화 요소가 있는가?  

완성도(25)  
- 요구 사항에 맞게 완벽하게 구현되었는가?  
- 기획의 구체성 및 구현도  

사업성(35)  
- 목표 시장과 타겟 고객 분석이 타당하고, 충분히 매력적인가?  
- 프로세스가 논리적이고 구현 가능한가?  

발표력(20)  
- 발표 능력 및 충실도 (발표 자료, 발표 내용의 개연성, 태도 및 자세)  
- 질의 응답 시 답변 내용 및 대응도  
  
---  
  
심사 위원 측의 많은 질문의 골자는 다음과 같이 정리할 수 있습니다.  
그래서 이걸 어디다가 쓸건데?  

&nbsp;  

💡  
개인적으로 다른 조들에 대한 평가를 예상해봤습니다.  
중요한 내용은 아니니 
[Self Feedback](#self-feedback) 
부분으로 넘어가셔도 무방합니다.  
&nbsp;  
  
---  
### 1조 Sentimental AI  
언어 감수성을 함유한 모델  
음... 어느 대학에서 팀으로 참여한걸로 알고있습니다.  
사업성 부분에서 많은 감점을 받았을것같습니다.  
발표 당시에 타겟에 대한 질문에 대해,  
회사에서 서류 올릴 때 검수용으로 사용하면 된다고 하셨는데,  
타겟 설정이 많이 아쉬웠습니다.  
차라리 컨텐츠 제작할 때 표현 검수용으로 서비스할 수 있다 제안하고,  
과거 논란이 된 컨텐츠에 대해 해당 모델을 적용한 결과를 보여줬다면 좀 더 설득력을 가질 수 있었습니다.  
  
&nbsp;  
  
### 2조 빈카니  
문장에 빈칸을 만들어주어 학습을 도와주는 문제 생성 서비스.  
팀원분 한분이 기대를 많이 하셔서 덩달아 주의 깊게 발표를 들었습니다.  
발표력, 완성도, 창의성까지 있었지만 아무래도 어딘가 좀 빈약했습니다.  
대학생들의 학습 보조라기엔 학습의 깊이가 얕은 수준에서만 가능할 듯 합니다.  
차라리 영어 원서의 영어 빈칸 채우기였다면 좀 더 사업성을 보여줄 수 있었을 듯 합니다.  
  
&nbsp;  
  
### 3조 킁킁  
**여행지 기반 향수 추천 서비스(필자 선정 명예 우수상)**  
개인적으로나 저희 팀원들이나 제일 기대했던 주제였습니다.  
대체 자연어처리로 어떻게 향수 추천까지 이끌어낼 수 있을까 굉장히 흥미로운 주제였습니다.  
여행지에 대한 향이 사람들의 기억에 각인된다는 점을 포인트로 잡고 발표를 이끌어나가는 부분이 굉장히 편안했습니다.  
참신성은 있지만, 여행지의 분위기와 맞는 향수를 추천해서 고객의 구매까지 이끌어낼 수 있을까? 라는 생각이 들었습니다.  
스타일까지는 여행지와 어울리도록 준비해 갈 수 있겠으나, 향수는 호불호가 많이 갈리는 만큼 개인화된 추천을 어느정도 적용했다면 어땠을까 생각됐습니다.  
게다가 조향사들이 애초부터 특정 지역을 타겟으로 디자인한 향수들이 시중에 많은 만큼 차별성이 없었다고 평가받았을 수도 있겠다는 생각이 들었습니다.  
그럼에도 왜 수상 못한건지 의문이 드는 팀이였습니다.  
향수의 향을 어떻게 확인할 수 있냐고 질문이 있었는데,  
그러면 이후에 8조에서도 술 맛은 어떻게 확인할 수 있냐고 같은 맥락의 질문이 들어왔어야 하는 게 아닌가 싶습니다.  
  
&nbsp;  
  
### 4조 스팸마요  
**모바일 통합형 피싱 탐지 모델**  
교육생들의 질문을 가장 많이 받은 조가 아닐까 싶습니다.  
발표자가 어떻게든 받아치는 모습이 인상적이었습니다.  
real-time으로 모바일에 이게 가능한 시스템이냐 질문했는데,  
추후에 서버로 음성 데이터를 보내서 추론 후에 보이스피싱 판독을 한다고 방향성을 말해주셨습니다.  
발표는 굉장히 잘 하셨는데, 창의성이나, 완성도, 사업성 부분에서 조금 감점을 받았을것같습니다.  
피싱은 굉장히 접근하기 어려운 분야 중에 하나입니다.  
짧은 시간 내에 결과물을 만들어낸 과거 '인공지능 전략과정'의 보이스 피싱 팀이 엄청났다는걸 체감합니다.  
  
&nbsp;  
  
### 5조 낭만 어부  (My Team)
**낚시성 기사 판별 및 유형 분류 서비스**  
창의성(13) -7  
- 새로운 가치를 제공하는가?(1)  
	특별히 새로운 가치를 제공하진 못했습니다.  
- 기존 문제를 해결하는가?(7)  
	기존 사회적 문제였던 낚시성 기사를 해소할 수 있습니다.  
- 차별화 요소가 있는가?(5)  
	기사가 어떤 유형의 낚시성 기사인지 판별해 줍니다.  
  
&nbsp;  
  
완성도(21) -4  
- 요구 사항에 맞게 완벽하게 구현되었는가?(9/10)  
	요구 사항에 맞게 완벽하게 구현했으나 상대적인 관점에서 약간 미흡할 순 있습니다.  
- 기획의 구체성 및 구현도(12/15)  
	기획을 구체적으로 설계하진 않았습니다(4.5/7.5)  
	구현도는 완벽합니다(7.5/7.5)  
  
&nbsp;  
  
사업성(23) -12  
- 목표 시장과 타겟 고객 분석이 타당하고, 충분히 매력적인가?(10/20)
	타겟 고객은 기본적으로 일반적인 인터넷 뉴스 기사 독자였는데,  
	심사위원측에서는 확장 방향성을 듣고 포털에 제공한다고 이해한 것 같습니다.  
	대형 뉴스 플랫폼이 한 개 뿐인데 이게 과연 매력적인 사업인가 생각하신 듯 합니다.  
	개인 사용자에게 제공한다면 객관적으로 충분히 괜찮은 서비스라고 생각합니다.  
- 프로세스가 논리적이고 구현 가능한가?(13/15)  
  
&nbsp;  
  
발표력(16) -4  
- 발표 능력 및 충실도 (발표 자료, 발표 내용의 개연성, 태도 및 자세)(7/10)  
	발표자께서 굉장히 안정적으로 발표해주셨습니다.  
	발표 자료 또한 빈틈 없었습니다.  
	태도 및 자세는 오히려 타 팀보다 괜찮았다고 생각합니다.  
	다만 발표 전달력은 조금 아쉬웠습니다.  
	기술적인 내용을 좀 줄였어도 괜찮지 않았을까.  
- 질의 응답 시 답변 내용 및 대응도(9/10)  
	답변 굉장히 잘했습니다.  
  
&nbsp;  
  
제가 생각하는 저희 5조 예상 점수는 73점입니다.  
사업성과 창의성 부분에서 많은 감점을 받았을 것으로 생각됩니다.  
  
&nbsp;  
  
### 6조 GrowHub  
**식집사를 위한 서비스 (우수상)**  
이때부터 갑자기 컴퓨터 비전이 나와서 의문이 들었습니다.  
자연어 처리 과정이라고 알고 있었는데 6조는 컴퓨터 비전으로 생육단계를 분류하는 모델로 식물 소셜 미디어를 만들었습니다.  
창의성은 이미 유사한 서비스가 있었기에 고점을 받진 못했을 듯 합니다.  
완성도 부분에서는 제대로 완성되진 않았으나, 전체적인 작품 수준이 높았습니다.  
다만 인공지능 관점에서 수준이 높은게 아닌 SW 해커톤에 나갔다면 준수할 수준이었습니다.  
식집사라는 타게팅과는 다르게 생육 단계 분류 가능한 식물 종류가 엽채류에 한정되어 요구 사항에 부합하는지는 모호합니다.  
사업성 부분에서는 굉장히 매력적이라고 생각됩니다.  
좋은 비즈니스 모델이라고 생각합니다.  
발표력도 괜찮으셔서 편안하게 내용을 들을 수 있었습니다.  
Yolo에 대한 개인적인 편견 때문에 재미있는 프로젝트로 보이진 않았습니다.  
  
&nbsp;  
  
### 7조 파이팅해보죠  
**올리브영 추천 아이템 챗봇**  
가슴이 아픈 조입니다.  
잘못 추천된 결과를 발표 자료로 가지고 나와서 스팸마요팀에 전직 올리브영 스탭이 계셔서 간장치기로 K.O를 당했습니다.  
특정 제품을 지성한테 추천해준다는 챗봇 응답을 보고,  
과거 올영 메이트셨던 4조의 팀원분이 해당 제품은 지성 타입한테 추천하지 않는 제품이라고 이의 제기를 하셨습니다.  
다른건 기억은 안나네요 너무나 인상적인 치명타였습니다.  
원래 교육생들의 질의는 사전 계획에 없었는데, 제가 담당자님께 여쭤보고 질문 릴레이를 시작한 게 미안해질 정도였습니다. 
기억나는 아쉬운 점은 전달력이 조금 부족했고, 시연 영상이 너무 늘어졌습니다.  
텍스트도 보이지 않아 뭘 보여주고 싶은건지 잘 보이지 않았습니다.  
설명이라도 곁들였다면 괜찮았을 듯 합니다.  
  
&nbsp;  
  
### 8조 다이어트닭  
**다이어트 식품 리뷰 분석 마케팅 전략 도출**  
기억이 안납니다.  
  
&nbsp;  
  
### 9조 우주 라이크 전통주 (최우수상)  
**음식과 페어링하기 좋은 전통주 추천**  
개인적으로도 잘했다고 생각하는 최우수상 팀입니다.  
창의성, 사업성, 완성도, 발표력 4박자를 다 갖춘 팀이었습니다. 9조에서도 Yolo모델을 사용해서 조금 애매했고, 코사인 유사도로 대충 끝냈다는 부분이 아쉬웠습니다. 다만 그걸 상쇄하는 주제의 참신함과 화려한 SW 기술 스택으로 완벽한 완성도를 보여줬습니다. 거기에 더불어 직접 데이터셋을 다양하게 구축해봤다는 경험이 괜찮게 보였습니다. 데이터 사이언스 노동의 70%가 데이터 수집인 만큼 열심히 한 게 보였습니다. 오후반인 점을 고려했을 때, 기술 역량이 왠만한 현직 주니어 수준이었습니다. 예상치 못한 수강생 질문들로 인해 시간이 많이 연장되서 불금에 빨리 퇴근하고 싶으셨던건지, 마지막 조는 질문 없이 마무리 되었습니다.  
  
&nbsp;  
&nbsp;  
  

결론: 이 프로그램은 **"아이디어"** 해커톤입니다.  
  
&nbsp;  
&nbsp;  
  
---
## Hackathon Review  
  
&nbsp;  
  
마무리하며...  
  
&nbsp;  
  
처음 포스터에는 지원 마감 기간이 10월 11일로 되어있고, 접수처 전산 상으로는 10월 13일까지로 되어있어서 헷갈렸습니다.  
일단 접수할 때에 학교 팀플 프로세스 정리하느라 정신이 없었어서 미루다가 13일 마감 직전에 어떻게든 접수를 했는데.  
알고보니 정식 마감일은 11일이고 이후에 접수한 인원은 정규 선발 인원에서 결원 발생 시에 추가 합격으로 처리가 된다고 합니다.  
  
&nbsp;  
  
저는 다행히 10월 20일에 담당자님께 연락이 와서 추가합격 인원으로 이번Hackathon Project에 참여할 수 있었습니다.  
짤막한 인터뷰 및 OT 때에 저 포함해서 3명이 Zoom으로 안내받았기 때문에 아마 보충인원은 총 3명이었던걸로 알고있습니다.  
원래 저는 오후반으로 신청했는데, 담당자님이 오전반 어떻냐고 물어보셔서 얼떨결에 오전반 괜찮다고 해버렸습니다.  
이 선택으로 인해 전공 수업과 해커톤 동시에 출석하느라 애 좀 먹었습니다.  
  
&nbsp;  
  
추합 OT를 마치고 바로 30분 후에 각 팀 미팅이 이루어졌습니다.  
저는 번갯불에 콩볶듯이, 추합되자마자 진행된 팀 미팅에서 팀장을 맡았습니다.  
이것 저것 버거운 일정들 투성이에 걱정되는 팀장 역할이었지만 결과적으론 만족스러운 결정이었습니다.  
  
&nbsp;  
  
저는 서지 자료 분류 서비스와 SNS 기반 키워드 분석 서비스를 제안했습니다.  
그래도 아이디어가 예비 주제까지는 올라갔습니다.  
아쉽게도 탈락했지만 돌이켜보면 저희의 어떤 주제도 심사위원분들의 기준을 충족시키지 못했을 것 같습니다.  
CV를 융합하지 않고 NLP라는 필드에서 벗어나지 않는 수준에서,  
~ 데이터를 구할 수 있다는 조건까지 만족하는 주제가,  
~ 창의성까지 지니도록 구상하는 건 다소 어려웠습니다.  
CV에는 자신이 있는 만큼 아이디어를 좀 더 다양하게 해도 된다는 걸 미리 알았다면 더 잘했을텐데 꽤나 아쉬웠습니다.  
그래도 제가 완전히 처음 접하는 NLP라는 분야에 조금 겁먹긴 했으나 새로운 시도를 했고, 좋은 결과로 마무리 할 수 있어서 뜻 깊은 경험이었습니다.  CV에 대한 주제를 배제한 덕에 NLP에 대한 공부를 집중적으로 할 수 있었다고 생각하기로 했습니다.  
빠르게 적응해서 프로젝트를 매끄럽게 진행할 수 있어서 다행이었습니다.  
이론을 바탕으로 문제점을 해결할 수 있어 뿌듯했습니다. 다시 한번 기본이 되는 이론의 중요성을 깨달았습니다.  
  
&nbsp;  
  

## Self Feedback
#### 잘한 점  
이슈 상황 분석 및 해결  
매끄럽게 진행한 프로젝트  
  
&nbsp;  
  
#### 못한 점  
좋은 아이디어 구상.  
Data-centric 접근한다고 해놓고, 막상 data는 하나하나 뜯어보지 않은 것.  
이전 대외 활동에서 발표 잘 못했던 게 계속 생각나서 발표 자원 못함.  
  
&nbsp;  
  
#### 개선할 점  
다방면으로 관심을 가지자  
문제 인식 관점을 가지자  
  
&nbsp;  
  
#### 성장한 점  
NLP 분야의 생성형 AI에 대한 개괄적인 이해.  
다양한 사람들과 인사이트 공유.  
내가 다 하려고 하는 습관을 버리고  
팀원들에게 적절한 업무를 맡길 수 있게 됨  
  
&nbsp;  
  
**다음 방향성**  
대외 활동은 잠시 쉬고, 이론 공부와 개인 역량 강화에 몰두    
  
&nbsp;  
&nbsp;  
  
---  

&nbsp;  

**BING Test2Image AI generator인 "Image Creator"를 사용해 만들어 본 프로젝트의 컨셉**  
<img src="/posts_img/CJ_Hackathon/shark_press_pulse.jpg" width="40%" height="30%" title="BANDALCOM" alt="shark_press_pulse.jpg">  

&nbsp;  

**서비스 시연 영상**  
<img width="80%" src="/posts_img/CJ_Hackathon/PressPulseTest.gif" width="60%" height="40%" title="BANDALCOM" alt="PressPulseTest.gif">

&nbsp;  

**수료증**  
<img src="/posts_img/CJ_Hackathon/certificate.jpg" width="40%" height="30%" title="BANDALCOM" alt="certificate.jpg">  

&nbsp;  

**발표 자료**  
@[PPT](https://bandalcom.github.io/assets/PressPulse.pdf)  

&nbsp;  

**단체 사진을 마지막으로···**   

<img src="/posts_img/CJ_Hackathon/PressPulseTeamPicture.jpg" width="60%" height="40%" title="BANDALCOM" alt="PressPulseTeamPicture.jpg">  
  
&nbsp;  
&nbsp;  
  
Thank you for reading!
  
---  

BANDALCOM🐻

