<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=180&section=header&text=Khoa%20(Sogo)%20Ho%20Nguyen&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=35" alt="Khoa (Sogo) Ho Nguyen" />

<img align="right" src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="160" alt="Animated developer at a desk" />

building ai and ml systems end to end, from training models to the backend, infrastructure, and hardware they run on.

Email: khoahonguyen0210@gmail.com

<a href="https://www.linkedin.com/in/khoa-ho-nguyen"><img src="https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin" /></a>
<a href="https://github.com/khoahonguyen0210"><img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white" alt="github" /></a>

<br clear="right" />

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f2027,50:203a43,100:2c5364&height=3" width="100%" alt="" />

### ai & machine learning

<table>
<tr>
<td width="100%" valign="top">

#### [text2sql ↗](https://github.com/khoahonguyen0210/text2sql) &nbsp;<sub>llm fine-tuning</sub>

a model that turns plain-English questions into SQL queries for a database. fine-tuned Qwen2.5-Coder-1.5B with QLoRA on one free Kaggle GPU, raising accuracy from 64.2% to 74.8% on databases it never saw, and built an API that checks every query is read-only before it runs.

`python` `pytorch` `hugging face transformers` `peft / qlora` `bitsandbytes` `fastapi` `sqlite`

</td>
</tr>
</table>

<table>
<tr>
<td width="100%" valign="top">

#### [ai earth intelligence ↗](https://github.com/khoahonguyen0210/Earth_intelligence) &nbsp;<sub>earth data q&a + forecasting</sub>

a platform where you ask questions about the Earth in plain English, like how many wildfires burned in a region last summer or what tomorrow's fire risk is. an LLM plans the steps, the system runs them on NASA satellite and weather data, and every number in the answer is checked against the real results.

`python` `xgboost` `pytorch` `gemini` `rag` `java` `spring boot` `go` `kafka` `react` `postgis` `aws`

</td>
</tr>
</table>

<table>
<tr>
<td width="100%" valign="top">

#### [ai supply chain planner ↗](https://github.com/khoahonguyen0210/AI_Supply_Chain) &nbsp;<sub>forecasting + optimization</sub>

a planning tool for supply chain teams. you ask something like "demand for earbuds will rise 20%, what should I do?" and it forecasts demand, ranks suppliers, and finds the cheapest purchase plan that fits every limit, with nothing ordered until a manager approves.

`python` `lightgbm` `rag` `pgvector` `java` `spring boot` `next.js` `kubernetes`

</td>
</tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f2027,50:203a43,100:2c5364&height=3" width="100%" alt="" />

### systems & hardware

<table>
<tr>
<td width="100%" valign="top">

#### [distributed task processing platform ↗](https://github.com/khoahonguyen0210/Distributed_Task_Processing_Platform) &nbsp;<sub>job queue</sub>

a system that spreads background jobs across many workers. built on Redis with retries, a dead-letter list for failed jobs, and atomic Lua scripts so no two workers take the same job, and a crashed worker's job gets picked up by another.

`python` `fastapi` `redis` `lua` `websockets` `docker`

</td>
</tr>
</table>

<table>
<tr>
<td width="100%" valign="top">

#### [ai gesture control ↗](https://github.com/khoahonguyen0210/AI_Gesture_Control) &nbsp;<sub>computer vision + embedded</sub>

control your mouse with hand gestures through a webcam. it tracks 21 points on your hand and sends commands to a simulated ESP32 board over a custom serial protocol, tested by fuzzing it against a second, independent parser.

`python` `opencv` `mediapipe` `c` `c++` `libfuzzer` `esp32`

</td>
</tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f2027,50:203a43,100:2c5364&height=3" width="100%" alt="" />

### team projects & collaborative engineering

<table>
<tr>
<td width="100%" valign="top">

#### [coral ↗](https://github.com/Andy-C18/Coral) &nbsp;·&nbsp; co-project manager &nbsp;<sub>location-based activity discovery · Texas A&amp;M Coding Club</sub>

co-leading a Texas A&M Coding Club project team as co-project manager, building a map-based app that helps students find people to do activities with: post an activity at a real place, discover nearby ones, and request to join. I plan the roadmap, split the work across the team, and keep the frontend, backend, and database pieces moving together.

`react` `typescript` `vite` `node.js` `fastify` `postgresql` `docker`

</td>
</tr>
</table>

<table>
<tr>
<td width="100%" valign="top">

#### [HowdyHack - rollwatch ↗](https://github.com/khoahonguyen0210/rollwatch) &nbsp;<sub>baby roll alert</sub>

built with a team of four at HowdyHack, Texas A&M's hackathon, a sensor pod for a baby's onesie that notices when the baby rolls onto their stomach, sounds an alarm, and buzzes the parent's phone. it is a prototype only, not a medical device.

`c++` `esp32-s3` `bluetooth le` `javascript` `webrtc` `ntfy`

</td>
</tr>
</table>

<table>
<tr>
<td width="100%" valign="top">

#### airline pricing and market demand forecasting &nbsp;<sub>Aggie Data Science Club × American Airlines</sub>

collaborating with an Aggie Data Science Club team on an industry-sponsored machine learning project for American Airlines. the work is under NDA, so the data and results stay private.

`python` `pandas` `scikit-learn` `xgboost` `seaborn`

</td>
</tr>
</table>

<table>
<tr>
<td width="100%" valign="top">

#### cuda vision &nbsp;<sub>gpu programming · Texas A&amp;M Coding Club</sub>

collaborating with a Texas A&M Coding Club team to learn GPU programming by writing CUDA C++ versions of compute-heavy tasks, then profiling and tuning them to run faster than the CPU version.

`cuda` `c++` `gpu profiling` `benchmarking`

</td>
</tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f2027,50:203a43,100:2c5364&height=3" width="100%" alt="" />

### currently interested in

`ai` · `machine learning` · `ml infrastructure` · `backend systems` · `gpu programming` · `embedded systems`

<div align="center">

Email: khoahonguyen0210@gmail.com

<a href="https://www.linkedin.com/in/khoa-ho-nguyen"><img src="https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin" /></a>
<a href="https://github.com/khoahonguyen0210"><img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white" alt="github" /></a>

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=110&section=footer" alt="" />
