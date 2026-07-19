# 대회 데이터셋 ipynb 분석 코칭

**Session ID:** ses_0875fea0fffesS6xDy1DQTbP4G
**Created:** 2026. 7. 19. 오후 1:26:25
**Updated:** 2026. 7. 19. 오후 1:29:14

---

## User

좀 봐줘라. 대회가 바로 모레에 있는데, 데이터 파일들 보이지? 출제 문제중에 저것들을 다 분석하는건 아니지만 저중에서 이제 문제에서 쓰는 데이터셋이 있다는 것이다. 아 대체 어떻게 학습해야하지? 일단 실습파일들도 있고하니... ipynb도 있으니... 제발 다 읽고 코칭좀 해줘 제발

---

## Assistant (Build · DeepSeek V4 Flash Free · 3.1s)

_Thinking:_

The user is asking for help with a competition that is the day after tomorrow. They want me to look at their data files, practice files, and ipynb notebooks to help them learn/study. They seem stressed and need coaching.

Let me first explore the workspace to understand what files are available.

**Tool: read**

**Input:**
```json
{
  "filePath": "C:\\Users\\Administrator\\Documents\\GitHub\\kw-competition-practice"
}
```

**Output:**
```
<path>C:\Users\Administrator\Documents\GitHub\kw-competition-practice</path>
<type>directory</type>
<entries>
.git/
.ipynb_checkpoints/
20260704-토요실습1.ipynb
20260704-토요실습1.zip
20260704-토요실습1/
20260705-일요실습1.ipynb
20260705-일요실습1.md
20260705-일요실습1.zip
20260705-일요실습1/
20260719-일요실습1.ipynb
경운대학교 AI-BigData All Datasets (원본).zip
경운대학교 AI-BigData All Datasets (원본)/
대한민국행복지도_건강.xlsx
대한민국행복지도_경제.xlsx
대한민국행복지도_관계및사회참여.xlsx
대한민국행복지도_교육.xlsx
대한민국행복지도_삶의만족도.xlsx
대한민국행복지도_안전.xlsx
대한민국행복지도_여가.xlsx
대한민국행복지도_환경.xlsx
aapl.csv
accel.csv
all_stocks.xls
all_stocks.xlsx
apple_data.csv
bank.csv
categories.csv
cereals.csv
chicago_food_inspections.csv
chinafood.xlsx
citibike (1).csv
citibike.csv
cloud.png
cloud2.png
code.xlsx
comment_rank.csv
covid.csv
covid19.csv
customers_reaction (1).csv
customers_reaction (2).csv
customers_reaction.csv
customers.csv
deliveries (1).csv
deliveries.csv
design/
disney.csv
dust.xlsx
dust1.xlsx
employees.csv
fine_dust.xlsx
foods_reaction.csv
fortune1000.csv
gitignore.txt
goog.csv
google_stocks.csv
groups1.csv
groups2.csv
happiness.csv
health_screenings_2020_1000ea.xlsx
hi.zip
ice_cream.csv
investments.csv
iris (1).csv
iris.csv
local_dust_20102019.xlsx
medical.csv
meteorite-landings.csv
minimum_wage.csv
mobile.csv
movies.csv
msft_modified.csv
msft_with_footer.csv
msft.csv
msft2.csv
msft2.xlsx
Multiple Worksheets (1).xlsx
Multiple Worksheets.xlsx
my_addr.xlsx
my_file.csv
name.txt
nation.xlsx
nba.csv
neighborhoods.csv
netflix.csv
nfl.csv
nobel.json
omh.csv
people_mf_202512_modi.csv
phone.xlsx
play (1).csv
play.csv
pokemon.csv
pop202101.csv
professor.csv
ratings_train.txt
README.md
recipes.csv
revolutionary_war.csv
sales_by_employee.csv
sample1.csv
sample2.csv
sample3_p.csv
sample3_p2c.csv
sample3_t.csv
sample3.csv
sample4.csv
sensors.csv
seoul_traffic_202605.xlsx
seoul_weather.csv
signup.csv
Single Worksheet.xlsx
sp500.csv
space_missions (1).csv
space_missions.csv
stocks_msft.xls
stocks_msft.xlsx
stocks.xlsx
stocks2.xls
stocks2.xlsx
storages/
Student Mental health.csv
t_ulsan_19462024.csv
temp_rain_20142024.xlsx
traffic202306.csv
traffic202306.xls
train (1).csv
train.csv
tv_shows.json
u_weather.csv
used_cars.csv
vaccine.csv
video_game_sales.csv
weather.csv
weather.txt
weather.xlsx
weather2.csv
week_1_sales.csv
week_1_satisfaction (1).csv
week_1_satisfaction (2).csv
week_1_satisfaction.csv
week_2_sales.csv

(141 entries)
</entries>
```

---

## Assistant (Build · DeepSeek V4 Flash Free · 3.5s)

_Thinking:_

This is a competition practice directory with many data files and some Jupyter notebooks. Let me read all the notebooks and markdown files to understand what the practice problems are about, and also check the README.

**Tool: read**

**Input:**
```json
{
  "filePath": "C:\\Users\\Administrator\\Documents\\GitHub\\kw-competition-practice\\README.md"
}
```

**Output:**
```
<path>C:\Users\Administrator\Documents\GitHub\kw-competition-practice\README.md</path>
<type>file</type>
<content>
1: # kw-competition-practice
2: 2026 경운대학교 지능형모빌리티 소프트웨어 경진대회(7.20 - 7.21)
3: 
4: ---
5: 공식 데이터셋 공유 링크: https://drive.google.com/drive/folders/1P6ebsbKydwtLPtsOeUBzpxdS9LzC8Lzl
6: 
7: 루트에 있는 데이터셋 파일들 중에는 데이터 분석 등 코딩 작업을 하며 데이터셋 파일 자체가 수정된 파일이 있습니다.
8: 경운대학교 AI-BigData All Datasets (원본)   폴더는 데이터셋들의 완전한 원본 상태 파일입니다.

(End of file - total 8 lines)
</content>
```

**Tool: read**

**Input:**
```json
{
  "filePath": "C:\\Users\\Administrator\\Documents\\GitHub\\kw-competition-practice\\20260704-토요실습1.ipynb"
}
```

**Output:**
```
<path>C:\Users\Administrator\Documents\GitHub\kw-competition-practice\20260704-토요실습1.ipynb</path>
<type>file</type>
<content>
1: {
2:  "cells": [
3:   {
4:    "cell_type": "markdown",
5:    "id": "da038d0d-24b2-4142-b671-105493364a05",
6:    "metadata": {},
7:    "source": [
8:     "# **20260704-토요실습1**"
9:    ]
10:   },
11:   {
12:    "cell_type": "markdown",
13:    "id": "6f2d32c7-bcb2-4dfd-9c3d-3764e22d84f3",
14:    "metadata": {},
15:    "source": [
16:     "### 먼저 전체를 출력"
17:    ]
18:   },
19:   {
20:    "cell_type": "code",
21:    "execution_count": 97,
22:    "id": "4e00c4f0-fbf7-4dcf-b91d-1ae4403476b4",
23:    "metadata": {},
24:    "outputs": [],
25:    "source": [
26:     "import matplotlib.pyplot as plt       # 맷플롯리브 시각화\n",
27:     "import pandas as pd                   # 판다스 데이터분석\n",
28:     "import numpy as np                    # 넘파이 수학계산\n",
29:     "                                      # 버스 스테이션이란 함수에, 시트 네임을 버스 스테이션으로 한 서울 트래픽 xlsx 파일을 읽을 결과를 저장한다. 변수이다.\n",
30:     "bus_station=pd.read_excel('seoul_traffic_202605.xlsx', sheet_name='bus_station')      "
31:    ]
32:   },
33:   {
34:    "cell_type": "code",
35:    "execution_count": 98,
36:    "id": "b530408c-be72-4b41-b44a-05ec0d0a1247",
37:    "metadata": {},
38:    "outputs": [
39:     {
40:      "data": {
41:       "text/html": [
42:        "<div>\n",
43:        "<style scoped>\n",
44:        "    .dataframe tbody tr th:only-of-type {\n",
45:        "        vertical-align: middle;\n",
46:        "    }\n",
47:        "\n",
48:        "    .dataframe tbody tr th {\n",
49:        "        vertical-align: top;\n",
50:        "    }\n",
51:        "\n",
52:        "    .dataframe thead th {\n",
53:        "        text-align: right;\n",
54:        "    }\n",
55:        "</style>\n",
56:        "<table border=\"1\" class=\"dataframe\">\n",
57:        "  <thead>\n",
58:        "    <tr style=\"text-align: right;\">\n",
59:        "      <th></th>\n",
60:        "      <th>사용월</th>\n",
61:        "      <th>노선ID</th>\n",
62:        "      <th>노선번호</th>\n",
63:        "      <th>노선명</th>\n",
64:        "      <th>버스정류장ID</th>\n",
65:        "      <th>버스정류장명</th>\n",
66:        "      <th>승차승객수</th>\n",
67:        "      <th>하차승객수</th>\n",
68:        "    </tr>\n",
69:        "  </thead>\n",
70:        "  <tbody>\n",
71:        "    <tr>\n",
72:        "      <th>0</th>\n",
73:        "      <td>2026-05</td>\n",
74:        "      <td>11110897</td>\n",
75:        "      <td>17</td>\n",
76:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
77:        "      <td>8503228</td>\n",
78:        "      <td>용산차고지(가상)</td>\n",
79:        "      <td>25</td>\n",
80:        "      <td>5</td>\n",
81:        "    </tr>\n",
82:        "    <tr>\n",
83:        "      <th>1</th>\n",
84:        "      <td>2026-05</td>\n",
85:        "      <td>11110897</td>\n",
86:        "      <td>17</td>\n",
87:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
88:        "      <td>8503189</td>\n",
89:        "      <td>신용산지하차도</td>\n",
90:        "      <td>735</td>\n",
91:        "      <td>21</td>\n",
92:        "    </tr>\n",
93:        "    <tr>\n",
94:        "      <th>2</th>\n",
95:        "      <td>2026-05</td>\n",
96:        "      <td>11110897</td>\n",
97:        "      <td>17</td>\n",
98:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
99:        "      <td>72992</td>\n",
100:        "      <td>용산역</td>\n",
101:        "      <td>22519</td>\n",
102:        "      <td>352</td>\n",
103:        "    </tr>\n",
104:        "    <tr>\n",
105:        "      <th>3</th>\n",
106:        "      <td>2026-05</td>\n",
107:        "      <td>11110897</td>\n",
108:        "      <td>17</td>\n",
109:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
110:        "      <td>72314</td>\n",
111:        "      <td>용산푸르지오써밋</td>\n",
112:        "      <td>1782</td>\n",
113:        "      <td>488</td>\n",
114:        "    </tr>\n",
115:        "    <tr>\n",
116:        "      <th>4</th>\n",
117:        "      <td>2026-05</td>\n",
118:        "      <td>11110897</td>\n",
119:        "      <td>17</td>\n",
120:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
121:        "      <td>72993</td>\n",
122:        "      <td>한강대교북단</td>\n",
123:        "      <td>7261</td>\n",
124:        "      <td>1998</td>\n",
125:        "    </tr>\n",
126:        "    <tr>\n",
127:        "      <th>...</th>\n",
128:        "      <td>...</td>\n",
129:        "      <td>...</td>\n",
130:        "      <td>...</td>\n",
131:        "      <td>...</td>\n",
132:        "      <td>...</td>\n",
133:        "      <td>...</td>\n",
134:        "      <td>...</td>\n",
135:        "      <td>...</td>\n",
136:        "    </tr>\n",
137:        "    <tr>\n",
138:        "      <th>41995</th>\n",
139:        "      <td>2026-05</td>\n",
140:        "      <td>92000001</td>\n",
141:        "      <td>한강버스01</td>\n",
142:        "      <td>한강버스01(마곡~잠실)</td>\n",
143:        "      <td>8503213</td>\n",
144:        "      <td>압구정</td>\n",
145:        "      <td>4899</td>\n",
146:        "      <td>3375</td>\n",
147:        "    </tr>\n",
148:        "    <tr>\n",
149:        "      <th>41996</th>\n",
150:        "      <td>2026-05</td>\n",
151:        "      <td>92000001</td>\n",
152:        "      <td>한강버스01</td>\n",
153:        "      <td>한강버스01(마곡~잠실)</td>\n",
154:        "      <td>8503214</td>\n",
155:        "      <td>옥수</td>\n",
156:        "      <td>5891</td>\n",
157:        "      <td>3566</td>\n",
158:        "    </tr>\n",
159:        "    <tr>\n",
160:        "      <th>41997</th>\n",
161:        "      <td>2026-05</td>\n",
162:        "      <td>92000001</td>\n",
163:        "      <td>한강버스01</td>\n",
164:        "      <td>한강버스01(마곡~잠실)</td>\n",
165:        "      <td>8503414</td>\n",
166:        "      <td>성수</td>\n",
167:        "      <td>4</td>\n",
168:        "      <td>4</td>\n",
169:        "    </tr>\n",
170:        "    <tr>\n",
171:        "      <th>41998</th>\n",
172:        "      <td>2026-05</td>\n",
173:        "      <td>92000001</td>\n",
174:        "      <td>한강버스01</td>\n",
175:        "      <td>한강버스01(마곡~잠실)</td>\n",
176:        "      <td>8503215</td>\n",
177:        "      <td>뚝섬</td>\n",
178:        "      <td>8736</td>\n",
179:        "      <td>6459</td>\n",
180:        "    </tr>\n",
181:        "    <tr>\n",
182:        "      <th>41999</th>\n",
183:        "      <td>2026-05</td>\n",
184:        "      <td>92000001</td>\n",
185:        "      <td>한강버스01</td>\n",
186:        "      <td>한강버스01(마곡~잠실)</td>\n",
187:        "      <td>8503216</td>\n",
188:        "      <td>잠실</td>\n",
189:        "      <td>9667</td>\n",
190:        "      <td>12434</td>\n",
191:        "    </tr>\n",
192:        "  </tbody>\n",
193:        "</table>\n",
194:        "<p>42000 rows × 8 columns</p>\n",
195:        "</div>"
196:       ],
197:       "text/plain": [
198:        "           사용월      노선ID    노선번호                    노선명  버스정류장ID     버스정류장명  \\\n",
199:        "0      2026-05  11110897      17  0017번(용산차고지~신용산역3번출구)  8503228  용산차고지(가상)   \n",
200:        "1      2026-05  11110897      17  0017번(용산차고지~신용산역3번출구)  8503189    신용산지하차도   \n",
201:        "2      2026-05  11110897      17  0017번(용산차고지~신용산역3번출구)    72992        용산역   \n",
202:        "3      2026-05  11110897      17  0017번(용산차고지~신용산역3번출구)    72314   용산푸르지오써밋   \n",
203:        "4      2026-05  11110897      17  0017번(용산차고지~신용산역3번출구)    72993     한강대교북단   \n",
204:        "...        ...       ...     ...                    ...      ...        ...   \n",
205:        "41995  2026-05  92000001  한강버스01          한강버스01(마곡~잠실)  8503213        압구정   \n",
206:        "41996  2026-05  92000001  한강버스01          한강버스01(마곡~잠실)  8503214         옥수   \n",
207:        "41997  2026-05  92000001  한강버스01          한강버스01(마곡~잠실)  8503414         성수   \n",
208:        "41998  2026-05  92000001  한강버스01          한강버스01(마곡~잠실)  8503215         뚝섬   \n",
209:        "41999  2026-05  92000001  한강버스01          한강버스01(마곡~잠실)  8503216         잠실   \n",
210:        "\n",
211:        "       승차승객수  하차승객수  \n",
212:        "0         25      5  \n",
213:        "1        735     21  \n",
214:        "2      22519    352  \n",
215:        "3       1782    488  \n",
216:        "4       7261   1998  \n",
217:        "...      ...    ...  \n",
218:        "41995   4899   3375  \n",
219:        "41996   5891   3566  \n",
220:        "41997      4      4  \n",
221:        "41998   8736   6459  \n",
222:        "41999   9667  12434  \n",
223:        "\n",
224:        "[42000 rows x 8 columns]"
225:       ]
226:      },
227:      "execution_count": 98,
228:      "metadata": {},
229:      "output_type": "execute_result"
230:     }
231:    ],
232:    "source": [
233:     "import matplotlib.pyplot as plt\n",
234:     "import pandas as pd\n",
235:     "import numpy as np\n",
236:     "\n",
237:     "bus_station=pd.read_excel('seoul_traffic_202605.xlsx', sheet_name='bus_station')\n",
238:     "bus_station"
239:    ]
240:   },
241:   {
242:    "cell_type": "code",
243:    "execution_count": null,
244:    "id": "8caf9f3c-157d-4757-876e-d7f9c9daf2b5",
245:    "metadata": {},
246:    "outputs": [],
247:    "source": []
248:   },
249:   {
250:    "cell_type": "markdown",
251:    "id": "27b34e4c-4e0e-4d30-a1e6-7455dc5f17bb",
252:    "metadata": {},
253:    "source": [
254:     "### 선택 출력"
255:    ]
256:   },
257:   {
258:    "cell_type": "code",
259:    "execution_count": 99,
260:    "id": "275fc5e8-9af3-41ed-b74c-1116dc04e7c4",
261:    "metadata": {},
262:    "outputs": [
263:     {
264:      "data": {
265:       "text/html": [
266:        "<div>\n",
267:        "<style scoped>\n",
268:        "    .dataframe tbody tr th:only-of-type {\n",
269:        "        vertical-align: middle;\n",
270:        "    }\n",
271:        "\n",
272:        "    .dataframe tbody tr th {\n",
273:        "        vertical-align: top;\n",
274:        "    }\n",
275:        "\n",
276:        "    .dataframe thead th {\n",
277:        "        text-align: right;\n",
278:        "    }\n",
279:        "</style>\n",
280:        "<table border=\"1\" class=\"dataframe\">\n",
281:        "  <thead>\n",
282:        "    <tr style=\"text-align: right;\">\n",
283:        "      <th></th>\n",
284:        "      <th>버스정류장ID</th>\n",
285:        "      <th>승차승객수</th>\n",
286:        "    </tr>\n",
287:        "  </thead>\n",
288:        "  <tbody>\n",
289:        "    <tr>\n",
290:        "      <th>0</th>\n",
291:        "      <td>8503228</td>\n",
292:        "      <td>25</td>\n",
293:        "    </tr>\n",
294:        "    <tr>\n",
295:        "      <th>1</th>\n",
296:        "      <td>8503189</td>\n",
297:        "      <td>735</td>\n",
298:        "    </tr>\n",
299:        "    <tr>\n",
300:        "      <th>2</th>\n",
301:        "      <td>72992</td>\n",
302:        "      <td>22519</td>\n",
303:        "    </tr>\n",
304:        "    <tr>\n",
305:        "      <th>3</th>\n",
306:        "      <td>72314</td>\n",
307:        "      <td>1782</td>\n",
308:        "    </tr>\n",
309:        "    <tr>\n",
310:        "      <th>4</th>\n",
311:        "      <td>72993</td>\n",
312:        "      <td>7261</td>\n",
313:        "    </tr>\n",
314:        "    <tr>\n",
315:        "      <th>...</th>\n",
316:        "      <td>...</td>\n",
317:        "      <td>...</td>\n",
318:        "    </tr>\n",
319:        "    <tr>\n",
320:        "      <th>41995</th>\n",
321:        "      <td>8503213</td>\n",
322:        "      <td>4899</td>\n",
323:        "    </tr>\n",
324:        "    <tr>\n",
325:        "      <th>41996</th>\n",
326:        "      <td>8503214</td>\n",
327:        "      <td>5891</td>\n",
328:        "    </tr>\n",
329:        "    <tr>\n",
330:        "      <th>41997</th>\n",
331:        "      <td>8503414</td>\n",
332:        "      <td>4</td>\n",
333:        "    </tr>\n",
334:        "    <tr>\n",
335:        "      <th>41998</th>\n",
336:        "      <td>8503215</td>\n",
337:        "      <td>8736</td>\n",
338:        "    </tr>\n",
339:        "    <tr>\n",
340:        "      <th>41999</th>\n",
341:        "      <td>8503216</td>\n",
342:        "      <td>9667</td>\n",
343:        "    </tr>\n",
344:        "  </tbody>\n",
345:        "</table>\n",
346:        "<p>42000 rows × 2 columns</p>\n",
347:        "</div>"
348:       ],
349:       "text/plain": [
350:        "       버스정류장ID  승차승객수\n",
351:        "0      8503228     25\n",
352:        "1      8503189    735\n",
353:        "2        72992  22519\n",
354:        "3        72314   1782\n",
355:        "4        72993   7261\n",
356:        "...        ...    ...\n",
357:        "41995  8503213   4899\n",
358:        "41996  8503214   5891\n",
359:        "41997  8503414      4\n",
360:        "41998  8503215   8736\n",
361:        "41999  8503216   9667\n",
362:        "\n",
363:        "[42000 rows x 2 columns]"
364:       ]
365:      },
366:      "execution_count": 99,
367:      "metadata": {},
368:      "output_type": "execute_result"
369:     }
370:    ],
371:    "source": [
372:     "bus_station[['버스정류장ID', '승차승객수']] # 두 가지 열만 선택"
373:    ]
374:   },
375:   {
376:    "cell_type": "code",
377:    "execution_count": 100,
378:    "id": "8ed254f1-118d-48da-ba7a-a7d6a438fd23",
379:    "metadata": {},
380:    "outputs": [
381:     {
382:      "data": {
383:       "text/html": [
384:        "<div>\n",
385:        "<style scoped>\n",
386:        "    .dataframe tbody tr th:only-of-type {\n",
387:        "        vertical-align: middle;\n",
388:        "    }\n",
389:        "\n",
390:        "    .dataframe tbody tr th {\n",
391:        "        vertical-align: top;\n",
392:        "    }\n",
393:        "\n",
394:        "    .dataframe thead th {\n",
395:        "        text-align: right;\n",
396:        "    }\n",
397:        "</style>\n",
398:        "<table border=\"1\" class=\"dataframe\">\n",
399:        "  <thead>\n",
400:        "    <tr style=\"text-align: right;\">\n",
401:        "      <th></th>\n",
402:        "      <th>노선번호</th>\n",
403:        "      <th>노선명</th>\n",
404:        "    </tr>\n",
405:        "  </thead>\n",
406:        "  <tbody>\n",
407:        "    <tr>\n",
408:        "      <th>0</th>\n",
409:        "      <td>17</td>\n",
410:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
411:        "    </tr>\n",
412:        "    <tr>\n",
413:        "      <th>1</th>\n",
414:        "      <td>17</td>\n",
415:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
416:        "    </tr>\n",
417:        "    <tr>\n",
418:        "      <th>2</th>\n",
419:        "      <td>17</td>\n",
420:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
421:        "    </tr>\n",
422:        "    <tr>\n",
423:        "      <th>3</th>\n",
424:        "      <td>17</td>\n",
425:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
426:        "    </tr>\n",
427:        "    <tr>\n",
428:        "      <th>4</th>\n",
429:        "      <td>17</td>\n",
430:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
431:        "    </tr>\n",
432:        "    <tr>\n",
433:        "      <th>...</th>\n",
434:        "      <td>...</td>\n",
435:        "      <td>...</td>\n",
436:        "    </tr>\n",
437:        "    <tr>\n",
438:        "      <th>41995</th>\n",
439:        "      <td>한강버스01</td>\n",
440:        "      <td>한강버스01(마곡~잠실)</td>\n",
441:        "    </tr>\n",
442:        "    <tr>\n",
443:        "      <th>41996</th>\n",
444:        "      <td>한강버스01</td>\n",
445:        "      <td>한강버스01(마곡~잠실)</td>\n",
446:        "    </tr>\n",
447:        "    <tr>\n",
448:        "      <th>41997</th>\n",
449:        "      <td>한강버스01</td>\n",
450:        "      <td>한강버스01(마곡~잠실)</td>\n",
451:        "    </tr>\n",
452:        "    <tr>\n",
453:        "      <th>41998</th>\n",
454:        "      <td>한강버스01</td>\n",
455:        "      <td>한강버스01(마곡~잠실)</td>\n",
456:        "    </tr>\n",
457:        "    <tr>\n",
458:        "      <th>41999</th>\n",
459:        "      <td>한강버스01</td>\n",
460:        "      <td>한강버스01(마곡~잠실)</td>\n",
461:        "    </tr>\n",
462:        "  </tbody>\n",
463:        "</table>\n",
464:        "<p>42000 rows × 2 columns</p>\n",
465:        "</div>"
466:       ],
467:       "text/plain": [
468:        "         노선번호                    노선명\n",
469:        "0          17  0017번(용산차고지~신용산역3번출구)\n",
470:        "1          17  0017번(용산차고지~신용산역3번출구)\n",
471:        "2          17  0017번(용산차고지~신용산역3번출구)\n",
472:        "3          17  0017번(용산차고지~신용산역3번출구)\n",
473:        "4          17  0017번(용산차고지~신용산역3번출구)\n",
474:        "...       ...                    ...\n",
475:        "41995  한강버스01          한강버스01(마곡~잠실)\n",
476:        "41996  한강버스01          한강버스01(마곡~잠실)\n",
477:        "41997  한강버스01          한강버스01(마곡~잠실)\n",
478:        "41998  한강버스01          한강버스01(마곡~잠실)\n",
479:        "41999  한강버스01          한강버스01(마곡~잠실)\n",
480:        "\n",
481:        "[42000 rows x 2 columns]"
482:       ]
483:      },
484:      "execution_count": 100,
485:      "metadata": {},
486:      "output_type": "execute_result"
487:     }
488:    ],
489:    "source": [
490:     "bus_station[['노선번호', '노선명']] # 두 가지 열만 선택"
491:    ]
492:   },
493:   {
494:    "cell_type": "code",
495:    "execution_count": 101,
496:    "id": "ae0817ce-4b8c-43bc-9cba-87d3d91a6901",
497:    "metadata": {},
498:    "outputs": [
499:     {
500:      "data": {
501:       "text/html": [
502:        "<div>\n",
503:        "<style scoped>\n",
504:        "    .dataframe tbody tr th:only-of-type {\n",
505:        "        vertical-align: middle;\n",
506:        "    }\n",
507:        "\n",
508:        "    .dataframe tbody tr th {\n",
509:        "        vertical-align: top;\n",
510:        "    }\n",
511:        "\n",
512:        "    .dataframe thead th {\n",
513:        "        text-align: right;\n",
514:        "    }\n",
515:        "</style>\n",
516:        "<table border=\"1\" class=\"dataframe\">\n",
517:        "  <thead>\n",
518:        "    <tr style=\"text-align: right;\">\n",
519:        "      <th></th>\n",
520:        "      <th>노선번호</th>\n",
521:        "      <th>노선명</th>\n",
522:        "      <th>버스정류장ID</th>\n",
523:        "      <th>버스정류장명</th>\n",
524:        "      <th>승차승객수</th>\n",
525:        "      <th>하차승객수</th>\n",
526:        "    </tr>\n",
527:        "  </thead>\n",
528:        "  <tbody>\n",
529:        "    <tr>\n",
530:        "      <th>0</th>\n",
531:        "      <td>17</td>\n",
532:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
533:        "      <td>8503228</td>\n",
534:        "      <td>용산차고지(가상)</td>\n",
535:        "      <td>25</td>\n",
536:        "      <td>5</td>\n",
537:        "    </tr>\n",
538:        "    <tr>\n",
539:        "      <th>1</th>\n",
540:        "      <td>17</td>\n",
541:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
542:        "      <td>8503189</td>\n",
543:        "      <td>신용산지하차도</td>\n",
544:        "      <td>735</td>\n",
545:        "      <td>21</td>\n",
546:        "    </tr>\n",
547:        "    <tr>\n",
548:        "      <th>2</th>\n",
549:        "      <td>17</td>\n",
550:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
551:        "      <td>72992</td>\n",
552:        "      <td>용산역</td>\n",
553:        "      <td>22519</td>\n",
554:        "      <td>352</td>\n",
555:        "    </tr>\n",
556:        "    <tr>\n",
557:        "      <th>3</th>\n",
558:        "      <td>17</td>\n",
559:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
560:        "      <td>72314</td>\n",
561:        "      <td>용산푸르지오써밋</td>\n",
562:        "      <td>1782</td>\n",
563:        "      <td>488</td>\n",
564:        "    </tr>\n",
565:        "    <tr>\n",
566:        "      <th>4</th>\n",
567:        "      <td>17</td>\n",
568:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
569:        "      <td>72993</td>\n",
570:        "      <td>한강대교북단</td>\n",
571:        "      <td>7261</td>\n",
572:        "      <td>1998</td>\n",
573:        "    </tr>\n",
574:        "    <tr>\n",
575:        "      <th>...</th>\n",
576:        "      <td>...</td>\n",
577:        "      <td>...</td>\n",
578:        "      <td>...</td>\n",
579:        "      <td>...</td>\n",
580:        "      <td>...</td>\n",
581:        "      <td>...</td>\n",
582:        "    </tr>\n",
583:        "    <tr>\n",
584:        "      <th>41995</th>\n",
585:        "      <td>한강버스01</td>\n",
586:        "      <td>한강버스01(마곡~잠실)</td>\n",
587:        "      <td>8503213</td>\n",
588:        "      <td>압구정</td>\n",
589:        "      <td>4899</td>\n",
590:        "      <td>3375</td>\n",
591:        "    </tr>\n",
592:        "    <tr>\n",
593:        "      <th>41996</th>\n",
594:        "      <td>한강버스01</td>\n",
595:        "      <td>한강버스01(마곡~잠실)</td>\n",
596:        "      <td>8503214</td>\n",
597:        "      <td>옥수</td>\n",
598:        "      <td>5891</td>\n",
599:        "      <td>3566</td>\n",
600:        "    </tr>\n",
601:        "    <tr>\n",
602:        "      <th>41997</th>\n",
603:        "      <td>한강버스01</td>\n",
604:        "      <td>한강버스01(마곡~잠실)</td>\n",
605:        "      <td>8503414</td>\n",
606:        "      <td>성수</td>\n",
607:        "      <td>4</td>\n",
608:        "      <td>4</td>\n",
609:        "    </tr>\n",
610:        "    <tr>\n",
611:        "      <th>41998</th>\n",
612:        "      <td>한강버스01</td>\n",
613:        "      <td>한강버스01(마곡~잠실)</td>\n",
614:        "      <td>8503215</td>\n",
615:        "      <td>뚝섬</td>\n",
616:        "      <td>8736</td>\n",
617:        "      <td>6459</td>\n",
618:        "    </tr>\n",
619:        "    <tr>\n",
620:        "      <th>41999</th>\n",
621:        "      <td>한강버스01</td>\n",
622:        "      <td>한강버스01(마곡~잠실)</td>\n",
623:        "      <td>8503216</td>\n",
624:        "      <td>잠실</td>\n",
625:        "      <td>9667</td>\n",
626:        "      <td>12434</td>\n",
627:        "    </tr>\n",
628:        "  </tbody>\n",
629:        "</table>\n",
630:        "<p>42000 rows × 6 columns</p>\n",
631:        "</div>"
632:       ],
633:       "text/plain": [
634:        "         노선번호                    노선명  버스정류장ID     버스정류장명  승차승객수  하차승객수\n",
635:        "0          17  0017번(용산차고지~신용산역3번출구)  8503228  용산차고지(가상)     25      5\n",
636:        "1          17  0017번(용산차고지~신용산역3번출구)  8503189    신용산지하차도    735     21\n",
637:        "2          17  0017번(용산차고지~신용산역3번출구)    72992        용산역  22519    352\n",
638:        "3          17  0017번(용산차고지~신용산역3번출구)    72314   용산푸르지오써밋   1782    488\n",
639:        "4          17  0017번(용산차고지~신용산역3번출구)    72993     한강대교북단   7261   1998\n",
640:        "...       ...                    ...      ...        ...    ...    ...\n",
641:        "41995  한강버스01          한강버스01(마곡~잠실)  8503213        압구정   4899   3375\n",
642:        "41996  한강버스01          한강버스01(마곡~잠실)  8503214         옥수   5891   3566\n",
643:        "41997  한강버스01          한강버스01(마곡~잠실)  8503414         성수      4      4\n",
644:        "41998  한강버스01          한강버스01(마곡~잠실)  8503215         뚝섬   8736   6459\n",
645:        "41999  한강버스01          한강버스01(마곡~잠실)  8503216         잠실   9667  12434\n",
646:        "\n",
647:        "[42000 rows x 6 columns]"
648:       ]
649:      },
650:      "execution_count": 101,
651:      "metadata": {},
652:      "output_type": "execute_result"
653:     }
654:    ],
655:    "source": [
656:     "bus_station[['노선번호','노선명','버스정류장ID','버스정류장명','승차승객수','하차승객수']] # 출력하고픈 열들을 지정"
657:    ]
658:   },
659:   {
660:    "cell_type": "code",
661:    "execution_count": 102,
662:    "id": "74d45ad3-e1cb-4f7c-a01d-3924a0a2b891",
663:    "metadata": {},
664:    "outputs": [
665:     {
666:      "data": {
667:       "text/html": [
668:        "<div>\n",
669:        "<style scoped>\n",
670:        "    .dataframe tbody tr th:only-of-type {\n",
671:        "        vertical-align: middle;\n",
672:        "    }\n",
673:        "\n",
674:        "    .dataframe tbody tr th {\n",
675:        "        vertical-align: top;\n",
676:        "    }\n",
677:        "\n",
678:        "    .dataframe thead th {\n",
679:        "        text-align: right;\n",
680:        "    }\n",
681:        "</style>\n",
682:        "<table border=\"1\" class=\"dataframe\">\n",
683:        "  <thead>\n",
684:        "    <tr style=\"text-align: right;\">\n",
685:        "      <th></th>\n",
686:        "      <th>노선번호</th>\n",
687:        "      <th>노선명</th>\n",
688:        "      <th>버스정류장ID</th>\n",
689:        "      <th>버스정류장명</th>\n",
690:        "      <th>승차승객수</th>\n",
691:        "      <th>하차승객수</th>\n",
692:        "    </tr>\n",
693:        "  </thead>\n",
694:        "  <tbody>\n",
695:        "    <tr>\n",
696:        "      <th>0</th>\n",
697:        "      <td>17</td>\n",
698:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
699:        "      <td>8503228</td>\n",
700:        "      <td>용산차고지(가상)</td>\n",
701:        "      <td>25</td>\n",
702:        "      <td>5</td>\n",
703:        "    </tr>\n",
704:        "    <tr>\n",
705:        "      <th>1</th>\n",
706:        "      <td>17</td>\n",
707:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
708:        "      <td>8503189</td>\n",
709:        "      <td>신용산지하차도</td>\n",
710:        "      <td>735</td>\n",
711:        "      <td>21</td>\n",
712:        "    </tr>\n",
713:        "    <tr>\n",
714:        "      <th>2</th>\n",
715:        "      <td>17</td>\n",
716:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
717:        "      <td>72992</td>\n",
718:        "      <td>용산역</td>\n",
719:        "      <td>22519</td>\n",
720:        "      <td>352</td>\n",
721:        "    </tr>\n",
722:        "    <tr>\n",
723:        "      <th>3</th>\n",
724:        "      <td>17</td>\n",
725:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
726:        "      <td>72314</td>\n",
727:        "      <td>용산푸르지오써밋</td>\n",
728:        "      <td>1782</td>\n",
729:        "      <td>488</td>\n",
730:        "    </tr>\n",
731:        "    <tr>\n",
732:        "      <th>4</th>\n",
733:        "      <td>17</td>\n",
734:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
735:        "      <td>72993</td>\n",
736:        "      <td>한강대교북단</td>\n",
737:        "      <td>7261</td>\n",
738:        "      <td>1998</td>\n",
739:        "    </tr>\n",
740:        "    <tr>\n",
741:        "      <th>5</th>\n",
742:        "      <td>17</td>\n",
743:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
744:        "      <td>72994</td>\n",
745:        "      <td>서부이촌동입구</td>\n",
746:        "      <td>2703</td>\n",
747:        "      <td>8094</td>\n",
748:        "    </tr>\n",
749:        "    <tr>\n",
750:        "      <th>6</th>\n",
751:        "      <td>17</td>\n",
752:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
753:        "      <td>72995</td>\n",
754:        "      <td>이촌2동대림아파트.새남터성지</td>\n",
755:        "      <td>1602</td>\n",
756:        "      <td>7579</td>\n",
757:        "    </tr>\n",
758:        "    <tr>\n",
759:        "      <th>7</th>\n",
760:        "      <td>17</td>\n",
761:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
762:        "      <td>72996</td>\n",
763:        "      <td>이촌2동주민센터</td>\n",
764:        "      <td>1605</td>\n",
765:        "      <td>5088</td>\n",
766:        "    </tr>\n",
767:        "    <tr>\n",
768:        "      <th>8</th>\n",
769:        "      <td>17</td>\n",
770:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
771:        "      <td>72997</td>\n",
772:        "      <td>이촌로입구.성촌공원앞</td>\n",
773:        "      <td>389</td>\n",
774:        "      <td>1298</td>\n",
775:        "    </tr>\n",
776:        "  </tbody>\n",
777:        "</table>\n",
778:        "</div>"
779:       ],
780:       "text/plain": [
781:        "  노선번호                    노선명  버스정류장ID           버스정류장명  승차승객수  하차승객수\n",
782:        "0   17  0017번(용산차고지~신용산역3번출구)  8503228        용산차고지(가상)     25      5\n",
783:        "1   17  0017번(용산차고지~신용산역3번출구)  8503189          신용산지하차도    735     21\n",
784:        "2   17  0017번(용산차고지~신용산역3번출구)    72992              용산역  22519    352\n",
785:        "3   17  0017번(용산차고지~신용산역3번출구)    72314         용산푸르지오써밋   1782    488\n",
786:        "4   17  0017번(용산차고지~신용산역3번출구)    72993           한강대교북단   7261   1998\n",
787:        "5   17  0017번(용산차고지~신용산역3번출구)    72994          서부이촌동입구   2703   8094\n",
788:        "6   17  0017번(용산차고지~신용산역3번출구)    72995  이촌2동대림아파트.새남터성지   1602   7579\n",
789:        "7   17  0017번(용산차고지~신용산역3번출구)    72996         이촌2동주민센터   1605   5088\n",
790:        "8   17  0017번(용산차고지~신용산역3번출구)    72997      이촌로입구.성촌공원앞    389   1298"
791:       ]
792:      },
793:      "execution_count": 102,
794:      "metadata": {},
795:      "output_type": "execute_result"
796:     }
797:    ],
798:    "source": [
799:     "bus_station[['노선번호','노선명','버스정류장ID','버스정류장명','승차승객수','하차승객수']].head(9)   # 상위 9 라인만 출력"
800:    ]
801:   },
802:   {
803:    "cell_type": "markdown",
804:    "id": "fe2b1ccf-cd25-4cb0-8252-99aaea7644ba",
805:    "metadata": {},
806:    "source": [
807:     "### 이름(Label)으로 접근하느냐(loc), 위치를 나타내는 정수(Integer)로 접근하느냐(iloc)"
808:    ]
809:   },
810:   {
811:    "cell_type": "code",
812:    "execution_count": 103,
813:    "id": "97fe4db3-8757-4091-9c6d-6e605cfb8d75",
814:    "metadata": {},
815:    "outputs": [
816:     {
817:      "data": {
818:       "text/html": [
819:        "<div>\n",
820:        "<style scoped>\n",
821:        "    .dataframe tbody tr th:only-of-type {\n",
822:        "        vertical-align: middle;\n",
823:        "    }\n",
824:        "\n",
825:        "    .dataframe tbody tr th {\n",
826:        "        vertical-align: top;\n",
827:        "    }\n",
828:        "\n",
829:        "    .dataframe thead th {\n",
830:        "        text-align: right;\n",
831:        "    }\n",
832:        "</style>\n",
833:        "<table border=\"1\" class=\"dataframe\">\n",
834:        "  <thead>\n",
835:        "    <tr style=\"text-align: right;\">\n",
836:        "      <th></th>\n",
837:        "      <th>사용월</th>\n",
838:        "      <th>노선ID</th>\n",
839:        "      <th>노선번호</th>\n",
840:        "      <th>노선명</th>\n",
841:        "      <th>버스정류장ID</th>\n",
842:        "      <th>버스정류장명</th>\n",
843:        "      <th>승차승객수</th>\n",
844:        "      <th>하차승객수</th>\n",
845:        "    </tr>\n",
846:        "  </thead>\n",
847:        "  <tbody>\n",
848:        "    <tr>\n",
849:        "      <th>1</th>\n",
850:        "      <td>2026-05</td>\n",
851:        "      <td>11110897</td>\n",
852:        "      <td>17</td>\n",
853:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
854:        "      <td>8503189</td>\n",
855:        "      <td>신용산지하차도</td>\n",
856:        "      <td>735</td>\n",
857:        "      <td>21</td>\n",
858:        "    </tr>\n",
859:        "    <tr>\n",
860:        "      <th>2</th>\n",
861:        "      <td>2026-05</td>\n",
862:        "      <td>11110897</td>\n",
863:        "      <td>17</td>\n",
864:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
865:        "      <td>72992</td>\n",
866:        "      <td>용산역</td>\n",
867:        "      <td>22519</td>\n",
868:        "      <td>352</td>\n",
869:        "    </tr>\n",
870:        "    <tr>\n",
871:        "      <th>3</th>\n",
872:        "      <td>2026-05</td>\n",
873:        "      <td>11110897</td>\n",
874:        "      <td>17</td>\n",
875:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
876:        "      <td>72314</td>\n",
877:        "      <td>용산푸르지오써밋</td>\n",
878:        "      <td>1782</td>\n",
879:        "      <td>488</td>\n",
880:        "    </tr>\n",
881:        "    <tr>\n",
882:        "      <th>4</th>\n",
883:        "      <td>2026-05</td>\n",
884:        "      <td>11110897</td>\n",
885:        "      <td>17</td>\n",
886:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
887:        "      <td>72993</td>\n",
888:        "      <td>한강대교북단</td>\n",
889:        "      <td>7261</td>\n",
890:        "      <td>1998</td>\n",
891:        "    </tr>\n",
892:        "  </tbody>\n",
893:        "</table>\n",
894:        "</div>"
895:       ],
896:       "text/plain": [
897:        "       사용월      노선ID 노선번호                    노선명  버스정류장ID    버스정류장명  승차승객수  \\\n",
898:        "1  2026-05  11110897   17  0017번(용산차고지~신용산역3번출구)  8503189   신용산지하차도    735   \n",
899:        "2  2026-05  11110897   17  0017번(용산차고지~신용산역3번출구)    72992       용산역  22519   \n",
900:        "3  2026-05  11110897   17  0017번(용산차고지~신용산역3번출구)    72314  용산푸르지오써밋   1782   \n",
901:        "4  2026-05  11110897   17  0017번(용산차고지~신용산역3번출구)    72993    한강대교북단   7261   \n",
902:        "\n",
903:        "   하차승객수  \n",
904:        "1     21  \n",
905:        "2    352  \n",
906:        "3    488  \n",
907:        "4   1998  "
908:       ]
909:      },
910:      "execution_count": 103,
911:      "metadata": {},
912:      "output_type": "execute_result"
913:     }
914:    ],
915:    "source": [
916:     "bus_station.iloc[1:5]"
917:    ]
918:   },
919:   {
920:    "cell_type": "code",
921:    "execution_count": null,
922:    "id": "b67ae23c-0577-46cf-aa9a-4635ae7202fe",
923:    "metadata": {},
924:    "outputs": [],
925:    "source": []
926:   },
927:   {
928:    "cell_type": "markdown",
929:    "id": "9b4e0acd-50ce-42bc-96f6-2ba35a5d5aaf",
930:    "metadata": {},
931:    "source": [
932:     "### loc iloc practice"
933:    ]
934:   },
935:   {
936:    "cell_type": "code",
937:    "execution_count": 104,
938:    "id": "07090a55-f00a-472b-9656-faf0d215c447",
939:    "metadata": {},
940:    "outputs": [
941:     {
942:      "data": {
943:       "text/plain": [
944:        "사용월                      2026-05\n",
945:        "노선ID                    11110897\n",
946:        "노선번호                          17\n",
947:        "노선명        0017번(용산차고지~신용산역3번출구)\n",
948:        "버스정류장ID                  8503189\n",
949:        "버스정류장명                   신용산지하차도\n",
950:        "승차승객수                        735\n",
951:        "하차승객수                         21\n",
952:        "Name: 1, dtype: object"
953:       ]
954:      },
955:      "execution_count": 104,
956:      "metadata": {},
957:      "output_type": "execute_result"
958:     }
959:    ],
960:    "source": [
961:     "bus_station.iloc[1]"
962:    ]
963:   },
964:   {
965:    "cell_type": "code",
966:    "execution_count": 105,
967:    "id": "61d0ba73-e7f5-42c8-9f17-421d2b5cadd2",
968:    "metadata": {},
969:    "outputs": [
970:     {
971:      "data": {
972:       "text/html": [
973:        "<div>\n",
974:        "<style scoped>\n",
975:        "    .dataframe tbody tr th:only-of-type {\n",
976:        "        vertical-align: middle;\n",
977:        "    }\n",
978:        "\n",
979:        "    .dataframe tbody tr th {\n",
980:        "        vertical-align: top;\n",
981:        "    }\n",
982:        "\n",
983:        "    .dataframe thead th {\n",
984:        "        text-align: right;\n",
985:        "    }\n",
986:        "</style>\n",
987:        "<table border=\"1\" class=\"dataframe\">\n",
988:        "  <thead>\n",
989:        "    <tr style=\"text-align: right;\">\n",
990:        "      <th></th>\n",
991:        "      <th>사용월</th>\n",
992:        "      <th>노선ID</th>\n",
993:        "      <th>노선번호</th>\n",
994:        "      <th>노선명</th>\n",
995:        "      <th>버스정류장ID</th>\n",
996:        "      <th>버스정류장명</th>\n",
997:        "      <th>승차승객수</th>\n",
998:        "      <th>하차승객수</th>\n",
999:        "    </tr>\n",
1000:        "  </thead>\n",
1001:        "  <tbody>\n",
1002:        "    <tr>\n",
1003:        "      <th>1</th>\n",
1004:        "      <td>2026-05</td>\n",
1005:        "      <td>11110897</td>\n",
1006:        "      <td>17</td>\n",
1007:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
1008:        "      <td>8503189</td>\n",
1009:        "      <td>신용산지하차도</td>\n",
1010:        "      <td>735</td>\n",
1011:        "      <td>21</td>\n",
1012:        "    </tr>\n",
1013:        "    <tr>\n",
1014:        "      <th>2</th>\n",
1015:        "      <td>2026-05</td>\n",
1016:        "      <td>11110897</td>\n",
1017:        "      <td>17</td>\n",
1018:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
1019:        "      <td>72992</td>\n",
1020:        "      <td>용산역</td>\n",
1021:        "      <td>22519</td>\n",
1022:        "      <td>352</td>\n",
1023:        "    </tr>\n",
1024:        "  </tbody>\n",
1025:        "</table>\n",
1026:        "</div>"
1027:       ],
1028:       "text/plain": [
1029:        "       사용월      노선ID 노선번호                    노선명  버스정류장ID   버스정류장명  승차승객수  \\\n",
1030:        "1  2026-05  11110897   17  0017번(용산차고지~신용산역3번출구)  8503189  신용산지하차도    735   \n",
1031:        "2  2026-05  11110897   17  0017번(용산차고지~신용산역3번출구)    72992      용산역  22519   \n",
1032:        "\n",
1033:        "   하차승객수  \n",
1034:        "1     21  \n",
1035:        "2    352  "
1036:       ]
1037:      },
1038:      "execution_count": 105,
1039:      "metadata": {},
1040:      "output_type": "execute_result"
1041:     }
1042:    ],
1043:    "source": [
1044:     "bus_station.iloc[[1,2]]     # 복수는 두개의 대괄호"
1045:    ]
1046:   },
1047:   {
1048:    "cell_type": "code",
1049:    "execution_count": 106,
1050:    "id": "f5ae1943-d8ff-44cb-8355-8769d2dbe4d4",
1051:    "metadata": {},
1052:    "outputs": [
1053:     {
1054:      "data": {
1055:       "text/html": [
1056:        "<div>\n",
1057:        "<style scoped>\n",
1058:        "    .dataframe tbody tr th:only-of-type {\n",
1059:        "        vertical-align: middle;\n",
1060:        "    }\n",
1061:        "\n",
1062:        "    .dataframe tbody tr th {\n",
1063:        "        vertical-align: top;\n",
1064:        "    }\n",
1065:        "\n",
1066:        "    .dataframe thead th {\n",
1067:        "        text-align: right;\n",
1068:        "    }\n",
1069:        "</style>\n",
1070:        "<table border=\"1\" class=\"dataframe\">\n",
1071:        "  <thead>\n",
1072:        "    <tr style=\"text-align: right;\">\n",
1073:        "      <th></th>\n",
1074:        "      <th>버스정류장명</th>\n",
1075:        "      <th>승차승객수</th>\n",
1076:        "      <th>하차승객수</th>\n",
1077:        "    </tr>\n",
1078:        "  </thead>\n",
1079:        "  <tbody>\n",
1080:        "    <tr>\n",
1081:        "      <th>0</th>\n",
1082:        "      <td>용산차고지(가상)</td>\n",
1083:        "      <td>25</td>\n",
1084:        "      <td>5</td>\n",
1085:        "    </tr>\n",
1086:        "    <tr>\n",
1087:        "      <th>1</th>\n",
1088:        "      <td>신용산지하차도</td>\n",
1089:        "      <td>735</td>\n",
1090:        "      <td>21</td>\n",
1091:        "    </tr>\n",
1092:        "    <tr>\n",
1093:        "      <th>2</th>\n",
1094:        "      <td>용산역</td>\n",
1095:        "      <td>22519</td>\n",
1096:        "      <td>352</td>\n",
1097:        "    </tr>\n",
1098:        "    <tr>\n",
1099:        "      <th>3</th>\n",
1100:        "      <td>용산푸르지오써밋</td>\n",
1101:        "      <td>1782</td>\n",
1102:        "      <td>488</td>\n",
1103:        "    </tr>\n",
1104:        "  </tbody>\n",
1105:        "</table>\n",
1106:        "</div>"
1107:       ],
1108:       "text/plain": [
1109:        "      버스정류장명  승차승객수  하차승객수\n",
1110:        "0  용산차고지(가상)     25      5\n",
1111:        "1    신용산지하차도    735     21\n",
1112:        "2        용산역  22519    352\n",
1113:        "3   용산푸르지오써밋   1782    488"
1114:       ]
1115:      },
1116:      "execution_count": 106,
1117:      "metadata": {},
1118:      "output_type": "execute_result"
1119:     }
1120:    ],
1121:    "source": [
1122:     "bus_station.loc[0:3, '버스정류장명':'하차승객수']        # 버스정류장명  부터 하차승객수 사이의(포함) 모든 열을 선택하며, 0번부터 3번째 행까지 출력한다."
1123:    ]
1124:   },
1125:   {
1126:    "cell_type": "code",
1127:    "execution_count": 107,
1128:    "id": "a7fb562c-1388-4aef-92bc-3dbed7c66d1a",
1129:    "metadata": {},
1130:    "outputs": [
1131:     {
1132:      "data": {
1133:       "text/html": [
1134:        "<div>\n",
1135:        "<style scoped>\n",
1136:        "    .dataframe tbody tr th:only-of-type {\n",
1137:        "        vertical-align: middle;\n",
1138:        "    }\n",
1139:        "\n",
1140:        "    .dataframe tbody tr th {\n",
1141:        "        vertical-align: top;\n",
1142:        "    }\n",
1143:        "\n",
1144:        "    .dataframe thead th {\n",
1145:        "        text-align: right;\n",
1146:        "    }\n",
1147:        "</style>\n",
1148:        "<table border=\"1\" class=\"dataframe\">\n",
1149:        "  <thead>\n",
1150:        "    <tr style=\"text-align: right;\">\n",
1151:        "      <th></th>\n",
1152:        "      <th>버스정류장명</th>\n",
1153:        "      <th>승차승객수</th>\n",
1154:        "      <th>하차승객수</th>\n",
1155:        "    </tr>\n",
1156:        "  </thead>\n",
1157:        "  <tbody>\n",
1158:        "    <tr>\n",
1159:        "      <th>0</th>\n",
1160:        "      <td>용산차고지(가상)</td>\n",
1161:        "      <td>25</td>\n",
1162:        "      <td>5</td>\n",
1163:        "    </tr>\n",
1164:        "    <tr>\n",
1165:        "      <th>1</th>\n",
1166:        "      <td>신용산지하차도</td>\n",
1167:        "      <td>735</td>\n",
1168:        "      <td>21</td>\n",
1169:        "    </tr>\n",
1170:        "    <tr>\n",
1171:        "      <th>2</th>\n",
1172:        "      <td>용산역</td>\n",
1173:        "      <td>22519</td>\n",
1174:        "      <td>352</td>\n",
1175:        "    </tr>\n",
1176:        "    <tr>\n",
1177:        "      <th>3</th>\n",
1178:        "      <td>용산푸르지오써밋</td>\n",
1179:        "      <td>1782</td>\n",
1180:        "      <td>488</td>\n",
1181:        "    </tr>\n",
1182:        "    <tr>\n",
1183:        "      <th>4</th>\n",
1184:        "      <td>한강대교북단</td>\n",
1185:        "      <td>7261</td>\n",
1186:        "      <td>1998</td>\n",
1187:        "    </tr>\n",
1188:        "  </tbody>\n",
1189:        "</table>\n",
1190:        "</div>"
1191:       ],
1192:       "text/plain": [
1193:        "      버스정류장명  승차승객수  하차승객수\n",
1194:        "0  용산차고지(가상)     25      5\n",
1195:        "1    신용산지하차도    735     21\n",
1196:        "2        용산역  22519    352\n",
1197:        "3   용산푸르지오써밋   1782    488\n",
1198:        "4     한강대교북단   7261   1998"
1199:       ]
1200:      },
1201:      "execution_count": 107,
1202:      "metadata": {},
1203:      "output_type": "execute_result"
1204:     }
1205:    ],
1206:    "source": [
1207:     "bus_station.loc[0:4, '버스정류장명':'하차승객수']"
1208:    ]
1209:   },
1210:   {
1211:    "cell_type": "markdown",
1212:    "id": "cea82a90-4679-436f-ab77-8a1e8635ac9e",
1213:    "metadata": {},
1214:    "source": [
1215:     "### 소트 정렬하기"
1216:    ]
1217:   },
1218:   {
1219:    "cell_type": "code",
1220:    "execution_count": 108,
1221:    "id": "0e57e9e9-4a30-461c-b1f1-e8f9e7423cc2",
1222:    "metadata": {},
1223:    "outputs": [
1224:     {
1225:      "data": {
1226:       "text/html": [
1227:        "<div>\n",
1228:        "<style scoped>\n",
1229:        "    .dataframe tbody tr th:only-of-type {\n",
1230:        "        vertical-align: middle;\n",
1231:        "    }\n",
1232:        "\n",
1233:        "    .dataframe tbody tr th {\n",
1234:        "        vertical-align: top;\n",
1235:        "    }\n",
1236:        "\n",
1237:        "    .dataframe thead th {\n",
1238:        "        text-align: right;\n",
1239:        "    }\n",
1240:        "</style>\n",
1241:        "<table border=\"1\" class=\"dataframe\">\n",
1242:        "  <thead>\n",
1243:        "    <tr style=\"text-align: right;\">\n",
1244:        "      <th></th>\n",
1245:        "      <th>사용월</th>\n",
1246:        "      <th>노선ID</th>\n",
1247:        "      <th>노선번호</th>\n",
1248:        "      <th>노선명</th>\n",
1249:        "      <th>버스정류장ID</th>\n",
1250:        "      <th>버스정류장명</th>\n",
1251:        "      <th>승차승객수</th>\n",
1252:        "      <th>하차승객수</th>\n",
1253:        "    </tr>\n",
1254:        "  </thead>\n",
1255:        "  <tbody>\n",
1256:        "    <tr>\n",
1257:        "      <th>37425</th>\n",
1258:        "      <td>2026-05</td>\n",
1259:        "      <td>11110590</td>\n",
1260:        "      <td>동대문01</td>\n",
1261:        "      <td>동대문01(회기역~경희의료원)</td>\n",
1262:        "      <td>9008470</td>\n",
1263:        "      <td>회기역</td>\n",
1264:        "      <td>128886</td>\n",
1265:        "      <td>62014</td>\n",
1266:        "    </tr>\n",
1267:        "    <tr>\n",
1268:        "      <th>40809</th>\n",
1269:        "      <td>2026-05</td>\n",
1270:        "      <td>11110696</td>\n",
1271:        "      <td>양천01</td>\n",
1272:        "      <td>양천01(등촌역~당산역)</td>\n",
1273:        "      <td>9008732</td>\n",
1274:        "      <td>당산역.지하철2호선</td>\n",
1275:        "      <td>95796</td>\n",
1276:        "      <td>75634</td>\n",
1277:        "    </tr>\n",
1278:        "    <tr>\n",
1279:        "      <th>38710</th>\n",
1280:        "      <td>2026-05</td>\n",
1281:        "      <td>11110641</td>\n",
1282:        "      <td>서대문03</td>\n",
1283:        "      <td>서대문03(홍은2동주민센터~신촌역)</td>\n",
1284:        "      <td>9013927</td>\n",
1285:        "      <td>신촌전철역</td>\n",
1286:        "      <td>91035</td>\n",
1287:        "      <td>30804</td>\n",
1288:        "    </tr>\n",
1289:        "    <tr>\n",
1290:        "      <th>37428</th>\n",
1291:        "      <td>2026-05</td>\n",
1292:        "      <td>11110590</td>\n",
1293:        "      <td>동대문01</td>\n",
1294:        "      <td>동대문01(회기역~경희의료원)</td>\n",
1295:        "      <td>9011737</td>\n",
1296:        "      <td>경희대의료원</td>\n",
1297:        "      <td>84937</td>\n",
1298:        "      <td>82737</td>\n",
1299:        "    </tr>\n",
1300:        "    <tr>\n",
1301:        "      <th>49</th>\n",
1302:        "      <td>2026-05</td>\n",
1303:        "      <td>11110475</td>\n",
1304:        "      <td>01A</td>\n",
1305:        "      <td>01A번(예장주차장~예장주차장)</td>\n",
1306:        "      <td>77296</td>\n",
1307:        "      <td>남산서울타워</td>\n",
1308:        "      <td>81252</td>\n",
1309:        "      <td>62410</td>\n",
1310:        "    </tr>\n",
1311:        "    <tr>\n",
1312:        "      <th>...</th>\n",
1313:        "      <td>...</td>\n",
1314:        "      <td>...</td>\n",
1315:        "      <td>...</td>\n",
1316:        "      <td>...</td>\n",
1317:        "      <td>...</td>\n",
1318:        "      <td>...</td>\n",
1319:        "      <td>...</td>\n",
1320:        "      <td>...</td>\n",
1321:        "    </tr>\n",
1322:        "    <tr>\n",
1323:        "      <th>31655</th>\n",
1324:        "      <td>2026-05</td>\n",
1325:        "      <td>41110152</td>\n",
1326:        "      <td>N37</td>\n",
1327:        "      <td>N37번(송파공영차고지~진관공영차고지)</td>\n",
1328:        "      <td>9010867</td>\n",
1329:        "      <td>복정역환승주차장</td>\n",
1330:        "      <td>0</td>\n",
1331:        "      <td>282</td>\n",
1332:        "    </tr>\n",
1333:        "    <tr>\n",
1334:        "      <th>6428</th>\n",
1335:        "      <td>2026-05</td>\n",
1336:        "      <td>11110358</td>\n",
1337:        "      <td>2016</td>\n",
1338:        "      <td>2016번(중랑차고지~이촌2동)</td>\n",
1339:        "      <td>7000038</td>\n",
1340:        "      <td>중랑공영차고지(가상)</td>\n",
1341:        "      <td>0</td>\n",
1342:        "      <td>17</td>\n",
1343:        "    </tr>\n",
1344:        "    <tr>\n",
1345:        "      <th>6288</th>\n",
1346:        "      <td>2026-05</td>\n",
1347:        "      <td>11110175</td>\n",
1348:        "      <td>2015</td>\n",
1349:        "      <td>2015번(신내공영차고지~동대문운동장)</td>\n",
1350:        "      <td>32570</td>\n",
1351:        "      <td>중랑공영차고지(가상)</td>\n",
1352:        "      <td>0</td>\n",
1353:        "      <td>20</td>\n",
1354:        "    </tr>\n",
1355:        "    <tr>\n",
1356:        "      <th>39221</th>\n",
1357:        "      <td>2026-05</td>\n",
1358:        "      <td>11410025</td>\n",
1359:        "      <td>서울09퇴근</td>\n",
1360:        "      <td>서울09퇴근(노원역~의정부시고산지구)</td>\n",
1361:        "      <td>8503180</td>\n",
1362:        "      <td>민락교</td>\n",
1363:        "      <td>0</td>\n",
1364:        "      <td>44</td>\n",
1365:        "    </tr>\n",
1366:        "    <tr>\n",
1367:        "      <th>39220</th>\n",
1368:        "      <td>2026-05</td>\n",
1369:        "      <td>11410025</td>\n",
1370:        "      <td>서울09퇴근</td>\n",
1371:        "      <td>서울09퇴근(노원역~의정부시고산지구)</td>\n",
1372:        "      <td>8503179</td>\n",
1373:        "      <td>정음마을고산2단지.고산종합사회복지관</td>\n",
1374:        "      <td>0</td>\n",
1375:        "      <td>56</td>\n",
1376:        "    </tr>\n",
1377:        "  </tbody>\n",
1378:        "</table>\n",
1379:        "<p>42000 rows × 8 columns</p>\n",
1380:        "</div>"
1381:       ],
1382:       "text/plain": [
1383:        "           사용월      노선ID    노선번호                    노선명  버스정류장ID  \\\n",
1384:        "37425  2026-05  11110590   동대문01       동대문01(회기역~경희의료원)  9008470   \n",
1385:        "40809  2026-05  11110696    양천01          양천01(등촌역~당산역)  9008732   \n",
1386:        "38710  2026-05  11110641   서대문03    서대문03(홍은2동주민센터~신촌역)  9013927   \n",
1387:        "37428  2026-05  11110590   동대문01       동대문01(회기역~경희의료원)  9011737   \n",
1388:        "49     2026-05  11110475     01A      01A번(예장주차장~예장주차장)    77296   \n",
1389:        "...        ...       ...     ...                    ...      ...   \n",
1390:        "31655  2026-05  41110152     N37  N37번(송파공영차고지~진관공영차고지)  9010867   \n",
1391:        "6428   2026-05  11110358    2016      2016번(중랑차고지~이촌2동)  7000038   \n",
1392:        "6288   2026-05  11110175    2015  2015번(신내공영차고지~동대문운동장)    32570   \n",
1393:        "39221  2026-05  11410025  서울09퇴근   서울09퇴근(노원역~의정부시고산지구)  8503180   \n",
1394:        "39220  2026-05  11410025  서울09퇴근   서울09퇴근(노원역~의정부시고산지구)  8503179   \n",
1395:        "\n",
1396:        "                    버스정류장명   승차승객수  하차승객수  \n",
1397:        "37425                  회기역  128886  62014  \n",
1398:        "40809           당산역.지하철2호선   95796  75634  \n",
1399:        "38710                신촌전철역   91035  30804  \n",
1400:        "37428               경희대의료원   84937  82737  \n",
1401:        "49                  남산서울타워   81252  62410  \n",
1402:        "...                    ...     ...    ...  \n",
1403:        "31655             복정역환승주차장       0    282  \n",
1404:        "6428           중랑공영차고지(가상)       0     17  \n",
1405:        "6288           중랑공영차고지(가상)       0     20  \n",
1406:        "39221                  민락교       0     44  \n",
1407:        "39220  정음마을고산2단지.고산종합사회복지관       0     56  \n",
1408:        "\n",
1409:        "[42000 rows x 8 columns]"
1410:       ]
1411:      },
1412:      "execution_count": 108,
1413:      "metadata": {},
1414:      "output_type": "execute_result"
1415:     }
1416:    ],
1417:    "source": [
1418:     "bus_station.sort_values(by='승차승객수', ascending=False)        # 승차승객수가 제일 큰 대로 내림차순 카운트다운"
1419:    ]
1420:   },
1421:   {
1422:    "cell_type": "code",
1423:    "execution_count": 109,
1424:    "id": "b20e648f",
1425:    "metadata": {},
1426:    "outputs": [
1427:     {
1428:      "data": {
1429:       "text/html": [
1430:        "<div>\n",
1431:        "<style scoped>\n",
1432:        "    .dataframe tbody tr th:only-of-type {\n",
1433:        "        vertical-align: middle;\n",
1434:        "    }\n",
1435:        "\n",
1436:        "    .dataframe tbody tr th {\n",
1437:        "        vertical-align: top;\n",
1438:        "    }\n",
1439:        "\n",
1440:        "    .dataframe thead th {\n",
1441:        "        text-align: right;\n",
1442:        "    }\n",
1443:        "</style>\n",
1444:        "<table border=\"1\" class=\"dataframe\">\n",
1445:        "  <thead>\n",
1446:        "    <tr style=\"text-align: right;\">\n",
1447:        "      <th></th>\n",
1448:        "      <th>사용월</th>\n",
1449:        "      <th>노선ID</th>\n",
1450:        "      <th>노선번호</th>\n",
1451:        "      <th>노선명</th>\n",
1452:        "      <th>버스정류장ID</th>\n",
1453:        "      <th>버스정류장명</th>\n",
1454:        "      <th>승차승객수</th>\n",
1455:        "      <th>하차승객수</th>\n",
1456:        "    </tr>\n",
1457:        "  </thead>\n",
1458:        "  <tbody>\n",
1459:        "    <tr>\n",
1460:        "      <th>30548</th>\n",
1461:        "      <td>2026-05</td>\n",
1462:        "      <td>11110378</td>\n",
1463:        "      <td>N15</td>\n",
1464:        "      <td>N15번(우이동성원아파트~남태령역)</td>\n",
1465:        "      <td>8502312</td>\n",
1466:        "      <td>사당자동차학원</td>\n",
1467:        "      <td>0</td>\n",
1468:        "      <td>40</td>\n",
1469:        "    </tr>\n",
1470:        "    <tr>\n",
1471:        "      <th>21321</th>\n",
1472:        "      <td>2026-05</td>\n",
1473:        "      <td>11110835</td>\n",
1474:        "      <td>6611</td>\n",
1475:        "      <td>6611번(개화역광역환승센터~한강버스마곡선착장)</td>\n",
1476:        "      <td>8502032</td>\n",
1477:        "      <td>강서공영차고지(종점가상)</td>\n",
1478:        "      <td>0</td>\n",
1479:        "      <td>2</td>\n",
1480:        "    </tr>\n",
1481:        "    <tr>\n",
1482:        "      <th>24864</th>\n",

(Output capped at 50 KB. Showing lines 1-1482. Use offset=1483 to continue.)
</content>
```

**Tool: read**

**Input:**
```json
{
  "filePath": "C:\\Users\\Administrator\\Documents\\GitHub\\kw-competition-practice\\20260705-일요실습1.ipynb"
}
```

**Output:**
```
<path>C:\Users\Administrator\Documents\GitHub\kw-competition-practice\20260705-일요실습1.ipynb</path>
<type>file</type>
<content>
1: {
2:  "cells": [
3:   {
4:    "cell_type": "markdown",
5:    "id": "575d9bdc-25e2-48f3-9196-590a9d735e85",
6:    "metadata": {},
7:    "source": [
8:     "# **20260705-일요실습1**"
9:    ]
10:   },
11:   {
12:    "cell_type": "markdown",
13:    "id": "19fd786d-4c66-40e1-9d6d-6b792a16792d",
14:    "metadata": {},
15:    "source": [
16:     "### 시작 - "
17:    ]
18:   },
19:   {
20:    "cell_type": "code",
21:    "execution_count": 50,
22:    "id": "b2fafc7b-965d-41d8-9728-2a40e6aad640",
23:    "metadata": {},
24:    "outputs": [],
25:    "source": [
26:     "import matplotlib.pyplot as plt       # 맷플롯리브 시각화\n",
27:     "import pandas as pd                   # 판다스 데이터분석\n",
28:     "import numpy as np                    # 넘파이 수학계산"
29:    ]
30:   },
31:   {
32:    "cell_type": "markdown",
33:    "id": "a43c6d3d-0b5b-4dc5-a4e9-22748b03532a",
34:    "metadata": {},
35:    "source": [
36:     "### 다시한번 서울지하철 - **seoul_traffic_202605.xlsx** (여기부터 이어서 시작)"
37:    ]
38:   },
39:   {
40:    "cell_type": "code",
41:    "execution_count": 51,
42:    "id": "57318666-db91-4010-87a9-72bd15d8d9e5",
43:    "metadata": {},
44:    "outputs": [
45:     {
46:      "data": {
47:       "text/html": [
48:        "<div>\n",
49:        "<style scoped>\n",
50:        "    .dataframe tbody tr th:only-of-type {\n",
51:        "        vertical-align: middle;\n",
52:        "    }\n",
53:        "\n",
54:        "    .dataframe tbody tr th {\n",
55:        "        vertical-align: top;\n",
56:        "    }\n",
57:        "\n",
58:        "    .dataframe thead th {\n",
59:        "        text-align: right;\n",
60:        "    }\n",
61:        "</style>\n",
62:        "<table border=\"1\" class=\"dataframe\">\n",
63:        "  <thead>\n",
64:        "    <tr style=\"text-align: right;\">\n",
65:        "      <th></th>\n",
66:        "      <th>사용월</th>\n",
67:        "      <th>호선명</th>\n",
68:        "      <th>역ID</th>\n",
69:        "      <th>지하철역</th>\n",
70:        "      <th>승차승객수</th>\n",
71:        "      <th>하차승객수</th>\n",
72:        "    </tr>\n",
73:        "  </thead>\n",
74:        "  <tbody>\n",
75:        "    <tr>\n",
76:        "      <th>0</th>\n",
77:        "      <td>2026-05</td>\n",
78:        "      <td>1호선</td>\n",
79:        "      <td>150</td>\n",
80:        "      <td>서울역</td>\n",
81:        "      <td>2449533</td>\n",
82:        "      <td>2405533</td>\n",
83:        "    </tr>\n",
84:        "    <tr>\n",
85:        "      <th>1</th>\n",
86:        "      <td>2026-05</td>\n",
87:        "      <td>1호선</td>\n",
88:        "      <td>151</td>\n",
89:        "      <td>시청</td>\n",
90:        "      <td>783572</td>\n",
91:        "      <td>790172</td>\n",
92:        "    </tr>\n",
93:        "    <tr>\n",
94:        "      <th>2</th>\n",
95:        "      <td>2026-05</td>\n",
96:        "      <td>1호선</td>\n",
97:        "      <td>152</td>\n",
98:        "      <td>종각</td>\n",
99:        "      <td>1202972</td>\n",
100:        "      <td>1157214</td>\n",
101:        "    </tr>\n",
102:        "    <tr>\n",
103:        "      <th>3</th>\n",
104:        "      <td>2026-05</td>\n",
105:        "      <td>1호선</td>\n",
106:        "      <td>153</td>\n",
107:        "      <td>종로3가</td>\n",
108:        "      <td>835118</td>\n",
109:        "      <td>745726</td>\n",
110:        "    </tr>\n",
111:        "    <tr>\n",
112:        "      <th>4</th>\n",
113:        "      <td>2026-05</td>\n",
114:        "      <td>1호선</td>\n",
115:        "      <td>154</td>\n",
116:        "      <td>종로5가</td>\n",
117:        "      <td>747033</td>\n",
118:        "      <td>725378</td>\n",
119:        "    </tr>\n",
120:        "    <tr>\n",
121:        "      <th>...</th>\n",
122:        "      <td>...</td>\n",
123:        "      <td>...</td>\n",
124:        "      <td>...</td>\n",
125:        "      <td>...</td>\n",
126:        "      <td>...</td>\n",
127:        "      <td>...</td>\n",
128:        "    </tr>\n",
129:        "    <tr>\n",
130:        "      <th>615</th>\n",
131:        "      <td>2026-05</td>\n",
132:        "      <td>신림선</td>\n",
133:        "      <td>4407</td>\n",
134:        "      <td>당곡</td>\n",
135:        "      <td>145646</td>\n",
136:        "      <td>138721</td>\n",
137:        "    </tr>\n",
138:        "    <tr>\n",
139:        "      <th>616</th>\n",
140:        "      <td>2026-05</td>\n",
141:        "      <td>신림선</td>\n",
142:        "      <td>4408</td>\n",
143:        "      <td>신림</td>\n",
144:        "      <td>72092</td>\n",
145:        "      <td>85438</td>\n",
146:        "    </tr>\n",
147:        "    <tr>\n",
148:        "      <th>617</th>\n",
149:        "      <td>2026-05</td>\n",
150:        "      <td>신림선</td>\n",
151:        "      <td>4409</td>\n",
152:        "      <td>서원</td>\n",
153:        "      <td>108743</td>\n",
154:        "      <td>96180</td>\n",
155:        "    </tr>\n",
156:        "    <tr>\n",
157:        "      <th>618</th>\n",
158:        "      <td>2026-05</td>\n",
159:        "      <td>신림선</td>\n",
160:        "      <td>4410</td>\n",
161:        "      <td>서울대벤처타운</td>\n",
162:        "      <td>309687</td>\n",
163:        "      <td>283165</td>\n",
164:        "    </tr>\n",
165:        "    <tr>\n",
166:        "      <th>619</th>\n",
167:        "      <td>2026-05</td>\n",
168:        "      <td>신림선</td>\n",
169:        "      <td>4411</td>\n",
170:        "      <td>관악산(서울대)</td>\n",
171:        "      <td>119147</td>\n",
172:        "      <td>117143</td>\n",
173:        "    </tr>\n",
174:        "  </tbody>\n",
175:        "</table>\n",
176:        "<p>620 rows × 6 columns</p>\n",
177:        "</div>"
178:       ],
179:       "text/plain": [
180:        "         사용월  호선명   역ID      지하철역    승차승객수    하차승객수\n",
181:        "0    2026-05  1호선   150       서울역  2449533  2405533\n",
182:        "1    2026-05  1호선   151        시청   783572   790172\n",
183:        "2    2026-05  1호선   152        종각  1202972  1157214\n",
184:        "3    2026-05  1호선   153      종로3가   835118   745726\n",
185:        "4    2026-05  1호선   154      종로5가   747033   725378\n",
186:        "..       ...  ...   ...       ...      ...      ...\n",
187:        "615  2026-05  신림선  4407        당곡   145646   138721\n",
188:        "616  2026-05  신림선  4408        신림    72092    85438\n",
189:        "617  2026-05  신림선  4409        서원   108743    96180\n",
190:        "618  2026-05  신림선  4410   서울대벤처타운   309687   283165\n",
191:        "619  2026-05  신림선  4411  관악산(서울대)   119147   117143\n",
192:        "\n",
193:        "[620 rows x 6 columns]"
194:       ]
195:      },
196:      "execution_count": 51,
197:      "metadata": {},
198:      "output_type": "execute_result"
199:     }
200:    ],
201:    "source": [
202:     "df_line=pd.read_excel('seoul_traffic_202605.xlsx', sheet_name='subway_line_station')\n",
203:     "df_line"
204:    ]
205:   },
206:   {
207:    "cell_type": "code",
208:    "execution_count": 52,
209:    "id": "789dbafd-d23c-4782-9edd-bfffb182294e",
210:    "metadata": {},
211:    "outputs": [
212:     {
213:      "data": {
214:       "text/html": [
215:        "<div>\n",
216:        "<style scoped>\n",
217:        "    .dataframe tbody tr th:only-of-type {\n",
218:        "        vertical-align: middle;\n",
219:        "    }\n",
220:        "\n",
221:        "    .dataframe tbody tr th {\n",
222:        "        vertical-align: top;\n",
223:        "    }\n",
224:        "\n",
225:        "    .dataframe thead th {\n",
226:        "        text-align: right;\n",
227:        "    }\n",
228:        "</style>\n",
229:        "<table border=\"1\" class=\"dataframe\">\n",
230:        "  <thead>\n",
231:        "    <tr style=\"text-align: right;\">\n",
232:        "      <th></th>\n",
233:        "      <th>사용월</th>\n",
234:        "      <th>호선명</th>\n",
235:        "      <th>역ID</th>\n",
236:        "      <th>지하철역</th>\n",
237:        "      <th>승차승객수</th>\n",
238:        "      <th>하차승객수</th>\n",
239:        "    </tr>\n",
240:        "  </thead>\n",
241:        "  <tbody>\n",
242:        "    <tr>\n",
243:        "      <th>0</th>\n",
244:        "      <td>2026-05</td>\n",
245:        "      <td>1호선</td>\n",
246:        "      <td>150</td>\n",
247:        "      <td>서울역</td>\n",
248:        "      <td>2449533</td>\n",
249:        "      <td>2405533</td>\n",
250:        "    </tr>\n",
251:        "    <tr>\n",
252:        "      <th>1</th>\n",
253:        "      <td>2026-05</td>\n",
254:        "      <td>1호선</td>\n",
255:        "      <td>151</td>\n",
256:        "      <td>시청</td>\n",
257:        "      <td>783572</td>\n",
258:        "      <td>790172</td>\n",
259:        "    </tr>\n",
260:        "    <tr>\n",
261:        "      <th>2</th>\n",
262:        "      <td>2026-05</td>\n",
263:        "      <td>1호선</td>\n",
264:        "      <td>152</td>\n",
265:        "      <td>종각</td>\n",
266:        "      <td>1202972</td>\n",
267:        "      <td>1157214</td>\n",
268:        "    </tr>\n",
269:        "    <tr>\n",
270:        "      <th>3</th>\n",
271:        "      <td>2026-05</td>\n",
272:        "      <td>1호선</td>\n",
273:        "      <td>153</td>\n",
274:        "      <td>종로3가</td>\n",
275:        "      <td>835118</td>\n",
276:        "      <td>745726</td>\n",
277:        "    </tr>\n",
278:        "    <tr>\n",
279:        "      <th>4</th>\n",
280:        "      <td>2026-05</td>\n",
281:        "      <td>1호선</td>\n",
282:        "      <td>154</td>\n",
283:        "      <td>종로5가</td>\n",
284:        "      <td>747033</td>\n",
285:        "      <td>725378</td>\n",
286:        "    </tr>\n",
287:        "    <tr>\n",
288:        "      <th>...</th>\n",
289:        "      <td>...</td>\n",
290:        "      <td>...</td>\n",
291:        "      <td>...</td>\n",
292:        "      <td>...</td>\n",
293:        "      <td>...</td>\n",
294:        "      <td>...</td>\n",
295:        "    </tr>\n",
296:        "    <tr>\n",
297:        "      <th>615</th>\n",
298:        "      <td>2026-05</td>\n",
299:        "      <td>신림선</td>\n",
300:        "      <td>4407</td>\n",
301:        "      <td>당곡</td>\n",
302:        "      <td>145646</td>\n",
303:        "      <td>138721</td>\n",
304:        "    </tr>\n",
305:        "    <tr>\n",
306:        "      <th>616</th>\n",
307:        "      <td>2026-05</td>\n",
308:        "      <td>신림선</td>\n",
309:        "      <td>4408</td>\n",
310:        "      <td>신림</td>\n",
311:        "      <td>72092</td>\n",
312:        "      <td>85438</td>\n",
313:        "    </tr>\n",
314:        "    <tr>\n",
315:        "      <th>617</th>\n",
316:        "      <td>2026-05</td>\n",
317:        "      <td>신림선</td>\n",
318:        "      <td>4409</td>\n",
319:        "      <td>서원</td>\n",
320:        "      <td>108743</td>\n",
321:        "      <td>96180</td>\n",
322:        "    </tr>\n",
323:        "    <tr>\n",
324:        "      <th>618</th>\n",
325:        "      <td>2026-05</td>\n",
326:        "      <td>신림선</td>\n",
327:        "      <td>4410</td>\n",
328:        "      <td>서울대벤처타운</td>\n",
329:        "      <td>309687</td>\n",
330:        "      <td>283165</td>\n",
331:        "    </tr>\n",
332:        "    <tr>\n",
333:        "      <th>619</th>\n",
334:        "      <td>2026-05</td>\n",
335:        "      <td>신림선</td>\n",
336:        "      <td>4411</td>\n",
337:        "      <td>관악산(서울대)</td>\n",
338:        "      <td>119147</td>\n",
339:        "      <td>117143</td>\n",
340:        "    </tr>\n",
341:        "  </tbody>\n",
342:        "</table>\n",
343:        "<p>620 rows × 6 columns</p>\n",
344:        "</div>"
345:       ],
346:       "text/plain": [
347:        "         사용월  호선명   역ID      지하철역    승차승객수    하차승객수\n",
348:        "0    2026-05  1호선   150       서울역  2449533  2405533\n",
349:        "1    2026-05  1호선   151        시청   783572   790172\n",
350:        "2    2026-05  1호선   152        종각  1202972  1157214\n",
351:        "3    2026-05  1호선   153      종로3가   835118   745726\n",
352:        "4    2026-05  1호선   154      종로5가   747033   725378\n",
353:        "..       ...  ...   ...       ...      ...      ...\n",
354:        "615  2026-05  신림선  4407        당곡   145646   138721\n",
355:        "616  2026-05  신림선  4408        신림    72092    85438\n",
356:        "617  2026-05  신림선  4409        서원   108743    96180\n",
357:        "618  2026-05  신림선  4410   서울대벤처타운   309687   283165\n",
358:        "619  2026-05  신림선  4411  관악산(서울대)   119147   117143\n",
359:        "\n",
360:        "[620 rows x 6 columns]"
361:       ]
362:      },
363:      "execution_count": 52,
364:      "metadata": {},
365:      "output_type": "execute_result"
366:     }
367:    ],
368:    "source": [
369:     "df_line=pd.read_excel('seoul_traffic_202605.xlsx', sheet_name='subway_line_station')\n",
370:     "df_line=df_line[['사용월','호선명','역ID','지하철역','승차승객수','하차승객수']]         \n",
371:     "df_line                                                                                #질문을 하니 교수님께서 직접 오셔서 ddf_line 새 정의를 해주셨다."
372:    ]
373:   },
374:   {
375:    "cell_type": "code",
376:    "execution_count": 53,
377:    "id": "3c45e9b7-8aea-4042-9de4-49771fac4cdc",
378:    "metadata": {},
379:    "outputs": [
380:     {
381:      "data": {
382:       "text/html": [
383:        "<div>\n",
384:        "<style scoped>\n",
385:        "    .dataframe tbody tr th:only-of-type {\n",
386:        "        vertical-align: middle;\n",
387:        "    }\n",
388:        "\n",
389:        "    .dataframe tbody tr th {\n",
390:        "        vertical-align: top;\n",
391:        "    }\n",
392:        "\n",
393:        "    .dataframe thead th {\n",
394:        "        text-align: right;\n",
395:        "    }\n",
396:        "</style>\n",
397:        "<table border=\"1\" class=\"dataframe\">\n",
398:        "  <thead>\n",
399:        "    <tr style=\"text-align: right;\">\n",
400:        "      <th></th>\n",
401:        "      <th>사용월</th>\n",
402:        "      <th>호선명</th>\n",
403:        "      <th>역ID</th>\n",
404:        "      <th>지하철역</th>\n",
405:        "      <th>승차승객수</th>\n",
406:        "      <th>하차승객수</th>\n",
407:        "      <th>총승하차승객수</th>\n",
408:        "    </tr>\n",
409:        "  </thead>\n",
410:        "  <tbody>\n",
411:        "    <tr>\n",
412:        "      <th>0</th>\n",
413:        "      <td>2026-05</td>\n",
414:        "      <td>1호선</td>\n",
415:        "      <td>150</td>\n",
416:        "      <td>서울역</td>\n",
417:        "      <td>2449533</td>\n",
418:        "      <td>2405533</td>\n",
419:        "      <td>4855066</td>\n",
420:        "    </tr>\n",
421:        "    <tr>\n",
422:        "      <th>1</th>\n",
423:        "      <td>2026-05</td>\n",
424:        "      <td>1호선</td>\n",
425:        "      <td>151</td>\n",
426:        "      <td>시청</td>\n",
427:        "      <td>783572</td>\n",
428:        "      <td>790172</td>\n",
429:        "      <td>1573744</td>\n",
430:        "    </tr>\n",
431:        "    <tr>\n",
432:        "      <th>2</th>\n",
433:        "      <td>2026-05</td>\n",
434:        "      <td>1호선</td>\n",
435:        "      <td>152</td>\n",
436:        "      <td>종각</td>\n",
437:        "      <td>1202972</td>\n",
438:        "      <td>1157214</td>\n",
439:        "      <td>2360186</td>\n",
440:        "    </tr>\n",
441:        "    <tr>\n",
442:        "      <th>3</th>\n",
443:        "      <td>2026-05</td>\n",
444:        "      <td>1호선</td>\n",
445:        "      <td>153</td>\n",
446:        "      <td>종로3가</td>\n",
447:        "      <td>835118</td>\n",
448:        "      <td>745726</td>\n",
449:        "      <td>1580844</td>\n",
450:        "    </tr>\n",
451:        "    <tr>\n",
452:        "      <th>4</th>\n",
453:        "      <td>2026-05</td>\n",
454:        "      <td>1호선</td>\n",
455:        "      <td>154</td>\n",
456:        "      <td>종로5가</td>\n",
457:        "      <td>747033</td>\n",
458:        "      <td>725378</td>\n",
459:        "      <td>1472411</td>\n",
460:        "    </tr>\n",
461:        "    <tr>\n",
462:        "      <th>...</th>\n",
463:        "      <td>...</td>\n",
464:        "      <td>...</td>\n",
465:        "      <td>...</td>\n",
466:        "      <td>...</td>\n",
467:        "      <td>...</td>\n",
468:        "      <td>...</td>\n",
469:        "      <td>...</td>\n",
470:        "    </tr>\n",
471:        "    <tr>\n",
472:        "      <th>615</th>\n",
473:        "      <td>2026-05</td>\n",
474:        "      <td>신림선</td>\n",
475:        "      <td>4407</td>\n",
476:        "      <td>당곡</td>\n",
477:        "      <td>145646</td>\n",
478:        "      <td>138721</td>\n",
479:        "      <td>284367</td>\n",
480:        "    </tr>\n",
481:        "    <tr>\n",
482:        "      <th>616</th>\n",
483:        "      <td>2026-05</td>\n",
484:        "      <td>신림선</td>\n",
485:        "      <td>4408</td>\n",
486:        "      <td>신림</td>\n",
487:        "      <td>72092</td>\n",
488:        "      <td>85438</td>\n",
489:        "      <td>157530</td>\n",
490:        "    </tr>\n",
491:        "    <tr>\n",
492:        "      <th>617</th>\n",
493:        "      <td>2026-05</td>\n",
494:        "      <td>신림선</td>\n",
495:        "      <td>4409</td>\n",
496:        "      <td>서원</td>\n",
497:        "      <td>108743</td>\n",
498:        "      <td>96180</td>\n",
499:        "      <td>204923</td>\n",
500:        "    </tr>\n",
501:        "    <tr>\n",
502:        "      <th>618</th>\n",
503:        "      <td>2026-05</td>\n",
504:        "      <td>신림선</td>\n",
505:        "      <td>4410</td>\n",
506:        "      <td>서울대벤처타운</td>\n",
507:        "      <td>309687</td>\n",
508:        "      <td>283165</td>\n",
509:        "      <td>592852</td>\n",
510:        "    </tr>\n",
511:        "    <tr>\n",
512:        "      <th>619</th>\n",
513:        "      <td>2026-05</td>\n",
514:        "      <td>신림선</td>\n",
515:        "      <td>4411</td>\n",
516:        "      <td>관악산(서울대)</td>\n",
517:        "      <td>119147</td>\n",
518:        "      <td>117143</td>\n",
519:        "      <td>236290</td>\n",
520:        "    </tr>\n",
521:        "  </tbody>\n",
522:        "</table>\n",
523:        "<p>620 rows × 7 columns</p>\n",
524:        "</div>"
525:       ],
526:       "text/plain": [
527:        "         사용월  호선명   역ID      지하철역    승차승객수    하차승객수  총승하차승객수\n",
528:        "0    2026-05  1호선   150       서울역  2449533  2405533  4855066\n",
529:        "1    2026-05  1호선   151        시청   783572   790172  1573744\n",
530:        "2    2026-05  1호선   152        종각  1202972  1157214  2360186\n",
531:        "3    2026-05  1호선   153      종로3가   835118   745726  1580844\n",
532:        "4    2026-05  1호선   154      종로5가   747033   725378  1472411\n",
533:        "..       ...  ...   ...       ...      ...      ...      ...\n",
534:        "615  2026-05  신림선  4407        당곡   145646   138721   284367\n",
535:        "616  2026-05  신림선  4408        신림    72092    85438   157530\n",
536:        "617  2026-05  신림선  4409        서원   108743    96180   204923\n",
537:        "618  2026-05  신림선  4410   서울대벤처타운   309687   283165   592852\n",
538:        "619  2026-05  신림선  4411  관악산(서울대)   119147   117143   236290\n",
539:        "\n",
540:        "[620 rows x 7 columns]"
541:       ]
542:      },
543:      "execution_count": 53,
544:      "metadata": {},
545:      "output_type": "execute_result"
546:     }
547:    ],
548:    "source": [
549:     "df_line['총승하차승객수']=df_line['승차승객수']+df_line['하차승객수']              #df_line 에 없는걸 선언한건 만들겠다는 뜻\n",
550:     "df_line                                                                           # 이제 출력한다."
551:    ]
552:   },
553:   {
554:    "cell_type": "markdown",
555:    "id": "5109e872-ed34-4515-bc2b-73558286658b",
556:    "metadata": {},
557:    "source": [
558:     "#### 총승하차승객수를 호선명을 기준으로 그룹바이"
559:    ]
560:   },
561:   {
562:    "cell_type": "code",
563:    "execution_count": 54,
564:    "id": "31cbfb48-047d-482d-9e25-cca2f8108467",
565:    "metadata": {},
566:    "outputs": [
567:     {
568:      "data": {
569:       "text/html": [
570:        "<div>\n",
571:        "<style scoped>\n",
572:        "    .dataframe tbody tr th:only-of-type {\n",
573:        "        vertical-align: middle;\n",
574:        "    }\n",
575:        "\n",
576:        "    .dataframe tbody tr th {\n",
577:        "        vertical-align: top;\n",
578:        "    }\n",
579:        "\n",
580:        "    .dataframe thead th {\n",
581:        "        text-align: right;\n",
582:        "    }\n",
583:        "</style>\n",
584:        "<table border=\"1\" class=\"dataframe\">\n",
585:        "  <thead>\n",
586:        "    <tr style=\"text-align: right;\">\n",
587:        "      <th></th>\n",
588:        "      <th>총승하차승객수</th>\n",
589:        "    </tr>\n",
590:        "    <tr>\n",
591:        "      <th>호선명</th>\n",
592:        "      <th></th>\n",
593:        "    </tr>\n",
594:        "  </thead>\n",
595:        "  <tbody>\n",
596:        "    <tr>\n",
597:        "      <th>1호선</th>\n",
598:        "      <td>16977364</td>\n",
599:        "    </tr>\n",
600:        "    <tr>\n",
601:        "      <th>2호선</th>\n",
602:        "      <td>87787733</td>\n",
603:        "    </tr>\n",
604:        "    <tr>\n",
605:        "      <th>3호선</th>\n",
606:        "      <td>33326606</td>\n",
607:        "    </tr>\n",
608:        "    <tr>\n",
609:        "      <th>4호선</th>\n",
610:        "      <td>34133290</td>\n",
611:        "    </tr>\n",
612:        "    <tr>\n",
613:        "      <th>5호선</th>\n",
614:        "      <td>40983496</td>\n",
615:        "    </tr>\n",
616:        "    <tr>\n",
617:        "      <th>6호선</th>\n",
618:        "      <td>21733007</td>\n",
619:        "    </tr>\n",
620:        "    <tr>\n",
621:        "      <th>7호선</th>\n",
622:        "      <td>36409565</td>\n",
623:        "    </tr>\n",
624:        "    <tr>\n",
625:        "      <th>8호선</th>\n",
626:        "      <td>12825792</td>\n",
627:        "    </tr>\n",
628:        "    <tr>\n",
629:        "      <th>9호선</th>\n",
630:        "      <td>17664094</td>\n",
631:        "    </tr>\n",
632:        "  </tbody>\n",
633:        "</table>\n",
634:        "</div>"
635:       ],
636:       "text/plain": [
637:        "      총승하차승객수\n",
638:        "호선명          \n",
639:        "1호선  16977364\n",
640:        "2호선  87787733\n",
641:        "3호선  33326606\n",
642:        "4호선  34133290\n",
643:        "5호선  40983496\n",
644:        "6호선  21733007\n",
645:        "7호선  36409565\n",
646:        "8호선  12825792\n",
647:        "9호선  17664094"
648:       ]
649:      },
650:      "execution_count": 54,
651:      "metadata": {},
652:      "output_type": "execute_result"
653:     }
654:    ],
655:    "source": [
656:     "df_line[['호선명','총승하차승객수']].groupby('호선명').sum().head(9)"
657:    ]
658:   },
659:   {
660:    "cell_type": "code",
661:    "execution_count": 55,
662:    "id": "decd9ce0-597b-4bbf-b0a4-b3a8e43aa40f",
663:    "metadata": {},
664:    "outputs": [
665:     {
666:      "data": {
667:       "image/png": "iVBORw0KGgoAAAANSUhEUgAAAicAAAHECAYAAADiaIpsAAAAOnRFWHRTb2Z0d2FyZQBNYXRwbG90bGliIHZlcnNpb24zLjEwLjAsIGh0dHBzOi8vbWF0cGxvdGxpYi5vcmcvlHJYcgAAAAlwSFlzAAAPYQAAD2EBqD+naQAAOttJREFUeJzt3Xd4VGXe//HPhJAJgRQhdBL6hkhAQQRhUarKqgiKBZCOBQtL93kUWVAUUEBFkMUCKFFQbEtAYZGmsKKAglgIHRKaSYA00khy//7wl3mYTQ9J5kzyfl3XXJL7PnPO9wsj8+HMPefYjDFGAAAAFuHh6gIAAACuRDgBAACWQjgBAACWQjgBAACWQjgBAACWQjgBAACWQjgBAACWQjgB3FhMTIw2btyY7/yxY8eUmppajhUV3U8//aSYmJir2se8efN09uzZq9rH9u3b9d13313VPvCnpKQk7dix46r2ceTIER0+fLiUKoK7IpzAbZ07d042m00nTpzIcz4zM1OLFy9Wz549VbduXdntdtntdtWrV0+9e/fWO++8o6ysrDKp7cSJE7LZbDp37lyB29WoUUObNm0q8fN37dqlwYMH5zt/7bXX6ocffiha0flYtmyZOnToUOzn7dixQzVq1Mh3fvDgwfrqq69yje/Zs0c2my3XeM7vSVxcnGNsypQpOnnyZLFru9Jbb72lZcuWXdU+8hIZGZmr3qK62tfFv/71LzVq1CjPuRkzZqhPnz7Fruns2bMaMWKEateuLW9vb91www1avXq10za//fabbr755nz3ceTIET300EMKCgpS9erVFRYWpnnz5ik9Pd2xzZw5c/TSSy8Vuz5ULIQTWNpdd92lGTNmlOi5AwYM0JtvvqmnnnpKv/76q1JTU5WSkqJ9+/Zp1KhRmj17toYPH16sfdpstgIf27ZtK1GtxdGkSRPH8fr27avz58871fDcc8+VeN/JycmKj493ely6dEnp6em5xuPj48ss3BXkyJEjioyMVGRkZLGf+/DDD+f6M/vwww+1dOnSXOOTJ0++qjrXrl0rSVq/fv1V7ccKYmNj1blzZ128eFFr1qzRzz//rNGjR+uRRx7RokWLirSPo0ePqkOHDvLz89PmzZsVHR2tBQsW6L333iswYKNy8nR1AUBZyMjIUEREhNauXau77rrLaa5evXoaPHiwMjMzNWbMmGLt98qPEObNm6effvpJK1eudIzVrFmzwOf/d9DKyMjQihUrnE6FP/DAA/Lx8cl3H/v371d2drYkKSIiQn//+9+dzh55e3sXpZU89e7dO98zLddcc02usZ07d+qmm27Kc/u0tDSlp6crOztbHh7F/3dQfHy808+JiYmSpM6dOxd7XzleffVVvfjii46fT506pe7du8vb21vffPONatWq5ZirXr16iY/zySef6Pnnn9cLL7ygCRMmKCgoSN27d893+6t9XZw9e1Z9+/Z1/BwfH6+YmBinM15dunTRG2+8UaJ+Xn75ZdWtW1dffPGF488yJCREgYGBGj16tIYPHy5fX98C97Fs2TKFhYXpn//8p2OsV69e+vTTTxUaGqpTp07le7YHlQ/hBJZmjFFJbv/k5eWlO++8U88++6wkqWvXrgoICJAkXbhwQVu3btXMmTM1YMCAYu23Xr16jl/7+PioSpUqTmOF+e/T8aNGjco1np6eXmA48fPzc/z6+PHjSkhIUHx8vJo0aaL09HTNnTvXMV/cMxvff/99rjFjjLKysuTpWby/Lvbv36/MzEzt3btXN9xwg9577z0tWbLEMV/YxzF5hSHpz9+rnBBRtWrVYtXk5+fn+P1bt26dnnjiCfXr10/JyckaMGCAlixZUmCIKExkZKRmzZqlTZs2KSIiQj179tSNN96oIUOG6L777tPkyZPzfAO+2tdFQECAU+jatWuXFi5c6DRWu3btEve1efNmDR06NFfIHDBggIYNG6bdu3erZ8+ehe4nr/+X... (line truncated to 2000 chars)
668:       "text/plain": [
669:        "<Figure size 640x480 with 1 Axes>"
670:       ]
671:      },
672:      "metadata": {},
673:      "output_type": "display_data"
674:     }
675:    ],
676:    "source": [
677:     "df_line[['호선명','총승하차승객수']].groupby('호선명').sum().head(9).plot(kind='bar', color='r', edgecolor='k', rot=0, legend=False)\n",
678:     "\n",
679:     "plt.rc('font', family='Malgun Gothic')  \n",
680:     "plt.title('서울 지하철 호선별 총 승하차 인원')\n",
681:     "plt.xlabel('호선명', loc='right')\n",
682:     "plt.ylabel('총 승하차 인원', loc='top')\n",
683:     "plt.show()"
684:    ]
685:   },
686:   {
687:    "cell_type": "markdown",
688:    "id": "efb3840f-c090-40cc-81a0-da6ed8f69380",
689:    "metadata": {},
690:    "source": [
691:     "#### 유임승객수를 호선명을 기준으로 그룹바이"
692:    ]
693:   },
694:   {
695:    "cell_type": "code",
696:    "execution_count": 56,
697:    "id": "3f2d5d72-f02f-47d8-af81-70a59b9a1692",
698:    "metadata": {},
699:    "outputs": [
700:     {
701:      "data": {
702:       "text/html": [
703:        "<div>\n",
704:        "<style scoped>\n",
705:        "    .dataframe tbody tr th:only-of-type {\n",
706:        "        vertical-align: middle;\n",
707:        "    }\n",
708:        "\n",
709:        "    .dataframe tbody tr th {\n",
710:        "        vertical-align: top;\n",
711:        "    }\n",
712:        "\n",
713:        "    .dataframe thead th {\n",
714:        "        text-align: right;\n",
715:        "    }\n",
716:        "</style>\n",
717:        "<table border=\"1\" class=\"dataframe\">\n",
718:        "  <thead>\n",
719:        "    <tr style=\"text-align: right;\">\n",
720:        "      <th></th>\n",
721:        "      <th>사용월</th>\n",
722:        "      <th>호선명</th>\n",
723:        "      <th>역ID</th>\n",
724:        "      <th>지하철역</th>\n",
725:        "      <th>유임승차</th>\n",
726:        "      <th>유임하차</th>\n",
727:        "      <th>무임승차</th>\n",
728:        "      <th>무임하차</th>\n",
729:        "    </tr>\n",
730:        "  </thead>\n",
731:        "  <tbody>\n",
732:        "    <tr>\n",
733:        "      <th>0</th>\n",
734:        "      <td>2026-05</td>\n",
735:        "      <td>1호선</td>\n",
736:        "      <td>150</td>\n",
737:        "      <td>서울역</td>\n",
738:        "      <td>2158192</td>\n",
739:        "      <td>2121832</td>\n",
740:        "      <td>291341</td>\n",
741:        "      <td>283701</td>\n",
742:        "    </tr>\n",
743:        "    <tr>\n",
744:        "      <th>1</th>\n",
745:        "      <td>2026-05</td>\n",
746:        "      <td>1호선</td>\n",
747:        "      <td>151</td>\n",
748:        "      <td>시청</td>\n",
749:        "      <td>679493</td>\n",
750:        "      <td>687420</td>\n",
751:        "      <td>104079</td>\n",
752:        "      <td>102752</td>\n",
753:        "    </tr>\n",
754:        "    <tr>\n",
755:        "      <th>2</th>\n",
756:        "      <td>2026-05</td>\n",
757:        "      <td>1호선</td>\n",
758:        "      <td>152</td>\n",
759:        "      <td>종각</td>\n",
760:        "      <td>1031847</td>\n",
761:        "      <td>997991</td>\n",
762:        "      <td>171125</td>\n",
763:        "      <td>159223</td>\n",
764:        "    </tr>\n",
765:        "    <tr>\n",
766:        "      <th>3</th>\n",
767:        "      <td>2026-05</td>\n",
768:        "      <td>1호선</td>\n",
769:        "      <td>153</td>\n",
770:        "      <td>종로3가</td>\n",
771:        "      <td>536436</td>\n",
772:        "      <td>474041</td>\n",
773:        "      <td>298682</td>\n",
774:        "      <td>271685</td>\n",
775:        "    </tr>\n",
776:        "    <tr>\n",
777:        "      <th>4</th>\n",
778:        "      <td>2026-05</td>\n",
779:        "      <td>1호선</td>\n",
780:        "      <td>154</td>\n",
781:        "      <td>종로5가</td>\n",
782:        "      <td>488431</td>\n",
783:        "      <td>474081</td>\n",
784:        "      <td>258602</td>\n",
785:        "      <td>251297</td>\n",
786:        "    </tr>\n",
787:        "  </tbody>\n",
788:        "</table>\n",
789:        "</div>"
790:       ],
791:       "text/plain": [
792:        "       사용월  호선명  역ID  지하철역     유임승차     유임하차    무임승차    무임하차\n",
793:        "0  2026-05  1호선  150   서울역  2158192  2121832  291341  283701\n",
794:        "1  2026-05  1호선  151    시청   679493   687420  104079  102752\n",
795:        "2  2026-05  1호선  152    종각  1031847   997991  171125  159223\n",
796:        "3  2026-05  1호선  153  종로3가   536436   474041  298682  271685\n",
797:        "4  2026-05  1호선  154  종로5가   488431   474081  258602  251297"
798:       ]
799:      },
800:      "execution_count": 56,
801:      "metadata": {},
802:      "output_type": "execute_result"
803:     }
804:    ],
805:    "source": [
806:     "import matplotlib.pyplot as plt\n",
807:     "import pandas as pd\n",
808:     "import numpy as np\n",
809:     "\n",
810:     "sub_pay=pd.read_excel('seoul_traffic_202605.xlsx', sheet_name='subway_pay')\n",
811:     "sub_pay.head()"
812:    ]
813:   },
814:   {
815:    "cell_type": "code",
816:    "execution_count": 57,
817:    "id": "73783c9e-a257-4fd7-b523-af27586ae0ba",
818:    "metadata": {},
819:    "outputs": [
820:     {
821:      "data": {
822:       "text/html": [
823:        "<div>\n",
824:        "<style scoped>\n",
825:        "    .dataframe tbody tr th:only-of-type {\n",
826:        "        vertical-align: middle;\n",
827:        "    }\n",
828:        "\n",
829:        "    .dataframe tbody tr th {\n",
830:        "        vertical-align: top;\n",
831:        "    }\n",
832:        "\n",
833:        "    .dataframe thead th {\n",
834:        "        text-align: right;\n",
835:        "    }\n",
836:        "</style>\n",
837:        "<table border=\"1\" class=\"dataframe\">\n",
838:        "  <thead>\n",
839:        "    <tr style=\"text-align: right;\">\n",
840:        "      <th></th>\n",
841:        "      <th>사용월</th>\n",
842:        "      <th>호선명</th>\n",
843:        "      <th>역ID</th>\n",
844:        "      <th>지하철역</th>\n",
845:        "      <th>유임승차</th>\n",
846:        "      <th>유임하차</th>\n",
847:        "      <th>무임승차</th>\n",
848:        "      <th>무임하차</th>\n",
849:        "      <th>유임승객수</th>\n",
850:        "    </tr>\n",
851:        "  </thead>\n",
852:        "  <tbody>\n",
853:        "    <tr>\n",
854:        "      <th>0</th>\n",
855:        "      <td>2026-05</td>\n",
856:        "      <td>1호선</td>\n",
857:        "      <td>150</td>\n",
858:        "      <td>서울역</td>\n",
859:        "      <td>2158192</td>\n",
860:        "      <td>2121832</td>\n",
861:        "      <td>291341</td>\n",
862:        "      <td>283701</td>\n",
863:        "      <td>4280024</td>\n",
864:        "    </tr>\n",
865:        "    <tr>\n",
866:        "      <th>1</th>\n",
867:        "      <td>2026-05</td>\n",
868:        "      <td>1호선</td>\n",
869:        "      <td>151</td>\n",
870:        "      <td>시청</td>\n",
871:        "      <td>679493</td>\n",
872:        "      <td>687420</td>\n",
873:        "      <td>104079</td>\n",
874:        "      <td>102752</td>\n",
875:        "      <td>1366913</td>\n",
876:        "    </tr>\n",
877:        "    <tr>\n",
878:        "      <th>2</th>\n",
879:        "      <td>2026-05</td>\n",
880:        "      <td>1호선</td>\n",
881:        "      <td>152</td>\n",
882:        "      <td>종각</td>\n",
883:        "      <td>1031847</td>\n",
884:        "      <td>997991</td>\n",
885:        "      <td>171125</td>\n",
886:        "      <td>159223</td>\n",
887:        "      <td>2029838</td>\n",
888:        "    </tr>\n",
889:        "    <tr>\n",
890:        "      <th>3</th>\n",
891:        "      <td>2026-05</td>\n",
892:        "      <td>1호선</td>\n",
893:        "      <td>153</td>\n",
894:        "      <td>종로3가</td>\n",
895:        "      <td>536436</td>\n",
896:        "      <td>474041</td>\n",
897:        "      <td>298682</td>\n",
898:        "      <td>271685</td>\n",
899:        "      <td>1010477</td>\n",
900:        "    </tr>\n",
901:        "    <tr>\n",
902:        "      <th>4</th>\n",
903:        "      <td>2026-05</td>\n",
904:        "      <td>1호선</td>\n",
905:        "      <td>154</td>\n",
906:        "      <td>종로5가</td>\n",
907:        "      <td>488431</td>\n",
908:        "      <td>474081</td>\n",
909:        "      <td>258602</td>\n",
910:        "      <td>251297</td>\n",
911:        "      <td>962512</td>\n",
912:        "    </tr>\n",
913:        "    <tr>\n",
914:        "      <th>...</th>\n",
915:        "      <td>...</td>\n",
916:        "      <td>...</td>\n",
917:        "      <td>...</td>\n",
918:        "      <td>...</td>\n",
919:        "      <td>...</td>\n",
920:        "      <td>...</td>\n",
921:        "      <td>...</td>\n",
922:        "      <td>...</td>\n",
923:        "      <td>...</td>\n",
924:        "    </tr>\n",
925:        "    <tr>\n",
926:        "      <th>615</th>\n",
927:        "      <td>2026-05</td>\n",
928:        "      <td>신림선</td>\n",
929:        "      <td>4407</td>\n",
930:        "      <td>당곡</td>\n",
931:        "      <td>99752</td>\n",
932:        "      <td>93933</td>\n",
933:        "      <td>45894</td>\n",
934:        "      <td>44788</td>\n",
935:        "      <td>193685</td>\n",
936:        "    </tr>\n",
937:        "    <tr>\n",
938:        "      <th>616</th>\n",
939:        "      <td>2026-05</td>\n",
940:        "      <td>신림선</td>\n",
941:        "      <td>4408</td>\n",
942:        "      <td>신림</td>\n",
943:        "      <td>48402</td>\n",
944:        "      <td>58913</td>\n",
945:        "      <td>23690</td>\n",
946:        "      <td>26525</td>\n",
947:        "      <td>107315</td>\n",
948:        "    </tr>\n",
949:        "    <tr>\n",
950:        "      <th>617</th>\n",
951:        "      <td>2026-05</td>\n",
952:        "      <td>신림선</td>\n",
953:        "      <td>4409</td>\n",
954:        "      <td>서원</td>\n",
955:        "      <td>77700</td>\n",
956:        "      <td>66014</td>\n",
957:        "      <td>31043</td>\n",
958:        "      <td>30166</td>\n",
959:        "      <td>143714</td>\n",
960:        "    </tr>\n",
961:        "    <tr>\n",
962:        "      <th>618</th>\n",
963:        "      <td>2026-05</td>\n",
964:        "      <td>신림선</td>\n",
965:        "      <td>4410</td>\n",
966:        "      <td>서울대벤처타운</td>\n",
967:        "      <td>230915</td>\n",
968:        "      <td>204782</td>\n",
969:        "      <td>78772</td>\n",
970:        "      <td>78383</td>\n",
971:        "      <td>435697</td>\n",
972:        "    </tr>\n",
973:        "    <tr>\n",
974:        "      <th>619</th>\n",
975:        "      <td>2026-05</td>\n",
976:        "      <td>신림선</td>\n",
977:        "      <td>4411</td>\n",
978:        "      <td>관악산(서울대)</td>\n",
979:        "      <td>70962</td>\n",
980:        "      <td>68958</td>\n",
981:        "      <td>48185</td>\n",
982:        "      <td>48185</td>\n",
983:        "      <td>139920</td>\n",
984:        "    </tr>\n",
985:        "  </tbody>\n",
986:        "</table>\n",
987:        "<p>620 rows × 9 columns</p>\n",
988:        "</div>"
989:       ],
990:       "text/plain": [
991:        "         사용월  호선명   역ID      지하철역     유임승차     유임하차    무임승차    무임하차    유임승객수\n",
992:        "0    2026-05  1호선   150       서울역  2158192  2121832  291341  283701  4280024\n",
993:        "1    2026-05  1호선   151        시청   679493   687420  104079  102752  1366913\n",
994:        "2    2026-05  1호선   152        종각  1031847   997991  171125  159223  2029838\n",
995:        "3    2026-05  1호선   153      종로3가   536436   474041  298682  271685  1010477\n",
996:        "4    2026-05  1호선   154      종로5가   488431   474081  258602  251297   962512\n",
997:        "..       ...  ...   ...       ...      ...      ...     ...     ...      ...\n",
998:        "615  2026-05  신림선  4407        당곡    99752    93933   45894   44788   193685\n",
999:        "616  2026-05  신림선  4408        신림    48402    58913   23690   26525   107315\n",
1000:        "617  2026-05  신림선  4409        서원    77700    66014   31043   30166   143714\n",
1001:        "618  2026-05  신림선  4410   서울대벤처타운   230915   204782   78772   78383   435697\n",
1002:        "619  2026-05  신림선  4411  관악산(서울대)    70962    68958   48185   48185   139920\n",
1003:        "\n",
1004:        "[620 rows x 9 columns]"
1005:       ]
1006:      },
1007:      "execution_count": 57,
1008:      "metadata": {},
1009:      "output_type": "execute_result"
1010:     }
1011:    ],
1012:    "source": [
1013:     "sub_pay['유임승객수']=sub_pay['유임승차']+sub_pay['유임하차']\n",
1014:     "sub_pay"
1015:    ]
1016:   },
1017:   {
1018:    "cell_type": "code",
1019:    "execution_count": 58,
1020:    "id": "d6c0193b-fe89-4d9a-b05e-48d7d6855fc7",
1021:    "metadata": {},
1022:    "outputs": [],
1023:    "source": [
1024:     "# sub_pay_sort 라는 새 변수 만들어서 다른 변수에 저장된 데이터프렘 데이터가 그래프화 되는 문제를 해결했다!"
1025:    ]
1026:   },
1027:   {
1028:    "cell_type": "code",
1029:    "execution_count": 59,
1030:    "id": "81d8f243-bcd2-4748-ad33-4d207aba44d7",
1031:    "metadata": {},
1032:    "outputs": [
1033:     {
1034:      "data": {
1035:       "text/html": [
1036:        "<div>\n",
1037:        "<style scoped>\n",
1038:        "    .dataframe tbody tr th:only-of-type {\n",
1039:        "        vertical-align: middle;\n",
1040:        "    }\n",
1041:        "\n",
1042:        "    .dataframe tbody tr th {\n",
1043:        "        vertical-align: top;\n",
1044:        "    }\n",
1045:        "\n",
1046:        "    .dataframe thead th {\n",
1047:        "        text-align: right;\n",
1048:        "    }\n",
1049:        "</style>\n",
1050:        "<table border=\"1\" class=\"dataframe\">\n",
1051:        "  <thead>\n",
1052:        "    <tr style=\"text-align: right;\">\n",
1053:        "      <th></th>\n",
1054:        "      <th>유임승객수</th>\n",
1055:        "    </tr>\n",
1056:        "    <tr>\n",
1057:        "      <th>호선명</th>\n",
1058:        "      <th></th>\n",
1059:        "    </tr>\n",
1060:        "  </thead>\n",
1061:        "  <tbody>\n",
1062:        "    <tr>\n",
1063:        "      <th>2호선</th>\n",
1064:        "      <td>76811863</td>\n",
1065:        "    </tr>\n",
1066:        "    <tr>\n",
1067:        "      <th>5호선</th>\n",
1068:        "      <td>32496535</td>\n",
1069:        "    </tr>\n",
1070:        "    <tr>\n",
1071:        "      <th>7호선</th>\n",
1072:        "      <td>29074731</td>\n",
1073:        "    </tr>\n",
1074:        "    <tr>\n",
1075:        "      <th>4호선</th>\n",
1076:        "      <td>27686611</td>\n",
1077:        "    </tr>\n",
1078:        "    <tr>\n",
1079:        "      <th>3호선</th>\n",
1080:        "      <td>26854631</td>\n",
1081:        "    </tr>\n",
1082:        "  </tbody>\n",
1083:        "</table>\n",
1084:        "</div>"
1085:       ],
1086:       "text/plain": [
1087:        "        유임승객수\n",
1088:        "호선명          \n",
1089:        "2호선  76811863\n",
1090:        "5호선  32496535\n",
1091:        "7호선  29074731\n",
1092:        "4호선  27686611\n",
1093:        "3호선  26854631"
1094:       ]
1095:      },
1096:      "execution_count": 59,
1097:      "metadata": {},
1098:      "output_type": "execute_result"
1099:     }
1100:    ],
1101:    "source": [
1102:     "sub_pay_sort=sub_pay[['호선명','유임승객수']].groupby('호선명').sum().sort_values(by='유임승객수', ascending=False).head(5)\n",
1103:     "sub_pay_sort"
1104:    ]
1105:   },
1106:   {
1107:    "cell_type": "code",
1108:    "execution_count": 60,
1109:    "id": "175f5da4-288a-44f1-b226-c9db99371fd0",
1110:    "metadata": {},
1111:    "outputs": [
1112:     {
1113:      "data": {
1114:       "image/png": "iVBORw0KGgoAAAANSUhEUgAAAicAAAHECAYAAADiaIpsAAAAOnRFWHRTb2Z0d2FyZQBNYXRwbG90bGliIHZlcnNpb24zLjEwLjAsIGh0dHBzOi8vbWF0cGxvdGxpYi5vcmcvlHJYcgAAAAlwSFlzAAAPYQAAD2EBqD+naQAAQj9JREFUeJzt3Xd0FXX+//HXTSOFFBCQFogUAUEURQEBqQqIIE0RFcG6uK4/wiKWr6LLioK6i7jLqtjoIoqAFEEERIQVBBQR6QSUEgw1CRgSkszvj9kbuKTdJPfemXvzfJwzh8nM3Jn3dcS8nE8Zh2EYhgAAAGwiyOoCAAAALkY4AQAAtkI4AQAAtkI4AQAAtkI4AQAAtkI4AQAAtkI4AQAAtkI4AcqhNWvWaPbs2VaXAQAFIpwANpOenq6xY8fq+uuvV3R0tEJDQ1W1alXdcsstmjVrloqbN3HlypVq166dIiIiFBcXp/79+2vv3r0ux6xatUrTpk1zq55z587J4XBo06ZNbh3vcDgKXNatW5e333mu8PBwrV692q3z3njjjXrjjTfcOtYqCxYsUEJCgiTpwIEDcjgcOnr0qLVFAX6IcALYyIkTJ3TDDTdo4cKFevbZZ7VlyxYdPXpUq1ev1q233qrhw4dr6NChhX5+6dKl6tWrl/r27atdu3bpu+++02WXXaY2bdro119/LVVNixYtyju3O44dO+ay/Pjjj5KU90u7NLKysrRv3z5t37691Odw6tq1a6EB6uLl0KFD+T47derUAo8t6p5cau/evW5d37nMnTu3zN8Z8DchVhcA4IJ//OMfys3N1erVqxUZGZm3/bLLLlPTpk3VoUMHtWrVSo8++qjatm2b7/NPPfWURo0apZEjR+Zte/fdd5WUlKSXX35Z7777bonqWbNmjR599FG98MILevPNN3XllVdq4MCBRX6mSpUqLj8vW7ZMV1xxhWrVqlWia19s7NixCg4O1qxZs/SnP/1JLVu2LPW55s2bp6ysrEL3Jycnq3nz5gXuGzhwoLp37+6y7emnny7R9evVq6djx465fXxMTEyJzg8EAp6cADayfft2tW3b1iWYXOzGG29UbGysduzYkW9fenq6tm3bpt69e+fb16dPH/33v/91u46DBw8qMTFRffv21dtvv60xY8Zo6dKlev755zV48GDt2rXL7XO98847+Z4sLF68WFOnTlVOTk6Rn83IyNCIESP09ttv68svv9SYMWPUtWtXzZkzx+3rXyomJkZVqlQpdKlUqVKhn42IiFD16tVdloiIiBJdPygoKO9aM2bMUFpamsv1K1SooHfeeUcRERGqUqWKwsLCSv1dAX9FOAFs5Morr9R///tfZWRkFLh/06ZNSk1N1ZVXXlnoOQrqk2IYhhwOR7HXHzdunFq0aKGmTZsqKChI27Zt09133y1JuuGGG7RlyxY1bdpUXbp0UdOmTfXYY48pNze30PPNmjVLu3fv1vDhw122f/DBBxo7dmyh4WTPnj167bXX1KhRI23fvl2bN29WixYtNGrUKM2ePVv/93//p9atW+vdd9/V3r17iw05djVx4kT9/PPPLtuSk5M1evRov/1OgCfQrAPYyJNPPqm5c+eqc+fOeuaZZ9SiRQvFxsbq6NGjWrp0qV555RUNHDhQN998c77PRkdH65prrtHixYvzNXt8/vnnBTYDXap///5q06aNWrdurfDw8Hz7o6Ki9Mwzz+ipp57STz/9pIyMDAUFFfz/OKtXr9af//xnzZ49W7GxsS775s+fr5YtWxZ4jeeee07/+te/dMstt2jmzJn5vmuPHj20e/duffzxx5ozZ45Gjx6tJUuWlKmppyDBwcH5tu3Zs0fffPONy7adO3eWuj9NVFSUzpw547ItPT1dDodDFStWLNU5gUBAOAFs5PLLL9cPP/ygCRMm6MUXX9TevXt17tw5xcXFqXnz5nr11Vc1ZMiQQj//2muvqV+/fnmj... (line truncated to 2000 chars)
1115:       "text/plain": [
1116:        "<Figure size 640x480 with 1 Axes>"
1117:       ]
1118:      },
1119:      "metadata": {},
1120:      "output_type": "display_data"
1121:     }
1122:    ],
1123:    "source": [
1124:     "sub_pay_sort.plot(kind='line', marker='o', color='r', legend=False)\n",
1125:     "\n",
1126:     "plt.rc('font', family='Malgun Gothic')\n",
1127:     "plt.title('유임승객수 그래프')\n",
1128:     "plt.xlabel('호선명')\n",
1129:     "plt.ylabel('유임승객 수(명)')\n",
1130:     "plt.show()"
1131:    ]
1132:   },
1133:   {
1134:    "cell_type": "markdown",
1135:    "id": "7efccee8-8aab-4f66-bf40-1092d5af464c",
1136:    "metadata": {},
1137:    "source": [
1138:     "#### 호선명을 기준으로 유임승차, 유임하차, 무임승차, 무임하차를 그룹바이"
1139:    ]
1140:   },
1141:   {
1142:    "cell_type": "code",
1143:    "execution_count": 69,
1144:    "id": "a75d08d7-f551-4fe1-9bbf-60e3a73011f1",
1145:    "metadata": {},
1146:    "outputs": [
1147:     {
1148:      "data": {
1149:       "text/html": [
1150:        "<div>\n",
1151:        "<style scoped>\n",
1152:        "    .dataframe tbody tr th:only-of-type {\n",
1153:        "        vertical-align: middle;\n",
1154:        "    }\n",
1155:        "\n",
1156:        "    .dataframe tbody tr th {\n",
1157:        "        vertical-align: top;\n",
1158:        "    }\n",
1159:        "\n",
1160:        "    .dataframe thead th {\n",
1161:        "        text-align: right;\n",
1162:        "    }\n",
1163:        "</style>\n",
1164:        "<table border=\"1\" class=\"dataframe\">\n",
1165:        "  <thead>\n",
1166:        "    <tr style=\"text-align: right;\">\n",
1167:        "      <th></th>\n",
1168:        "      <th>유임승차</th>\n",
1169:        "      <th>유임하차</th>\n",
1170:        "      <th>무임승차</th>\n",
1171:        "      <th>무임하차</th>\n",
1172:        "    </tr>\n",
1173:        "    <tr>\n",
1174:        "      <th>호선명</th>\n",
1175:        "      <th></th>\n",
1176:        "      <th></th>\n",
1177:        "      <th></th>\n",
1178:        "      <th></th>\n",
1179:        "    </tr>\n",
1180:        "  </thead>\n",
1181:        "  <tbody>\n",
1182:        "    <tr>\n",
1183:        "      <th>1호선</th>\n",
1184:        "      <td>6419075</td>\n",
1185:        "      <td>6270702</td>\n",
1186:        "      <td>2159937</td>\n",
1187:        "      <td>2127650</td>\n",
1188:        "    </tr>\n",
1189:        "    <tr>\n",
1190:        "      <th>2호선</th>\n",
1191:        "      <td>38115487</td>\n",
1192:        "      <td>38696376</td>\n",
1193:        "      <td>5520166</td>\n",
1194:        "      <td>5455704</td>\n",
1195:        "    </tr>\n",
1196:        "    <tr>\n",
1197:        "      <th>3호선</th>\n",
1198:        "      <td>13490732</td>\n",
1199:        "      <td>13363899</td>\n",
1200:        "      <td>3268277</td>\n",
1201:        "      <td>3203698</td>\n",
1202:        "    </tr>\n",
1203:        "    <tr>\n",
1204:        "      <th>4호선</th>\n",
1205:        "      <td>13684728</td>\n",
1206:        "      <td>14001883</td>\n",
1207:        "      <td>3212014</td>\n",
1208:        "      <td>3234665</td>\n",
1209:        "    </tr>\n",
1210:        "    <tr>\n",
1211:        "      <th>5호선</th>\n",
1212:        "      <td>16337913</td>\n",
1213:        "      <td>16158622</td>\n",
1214:        "      <td>4277487</td>\n",
1215:        "      <td>4209474</td>\n",
1216:        "    </tr>\n",
1217:        "    <tr>\n",
1218:        "      <th>6호선</th>\n",
1219:        "      <td>8834967</td>\n",
1220:        "      <td>8837115</td>\n",
1221:        "      <td>2046010</td>\n",
1222:        "      <td>2014915</td>\n",
1223:        "    </tr>\n",
1224:        "    <tr>\n",
1225:        "      <th>7호선</th>\n",
1226:        "      <td>14658705</td>\n",
1227:        "      <td>14416026</td>\n",
1228:        "      <td>3686763</td>\n",
1229:        "      <td>3648071</td>\n",
1230:        "    </tr>\n",
1231:        "    <tr>\n",
1232:        "      <th>8호선</th>\n",
1233:        "      <td>4946249</td>\n",
1234:        "      <td>5016754</td>\n",
1235:        "      <td>1446371</td>\n",
1236:        "      <td>1416418</td>\n",
1237:        "    </tr>\n",
1238:        "    <tr>\n",
1239:        "      <th>9호선</th>\n",
1240:        "      <td>7357970</td>\n",
1241:        "      <td>7500446</td>\n",
1242:        "      <td>1404420</td>\n",
1243:        "      <td>1401258</td>\n",
1244:        "    </tr>\n",
1245:        "  </tbody>\n",
1246:        "</table>\n",
1247:        "</div>"
1248:       ],
1249:       "text/plain": [
1250:        "         유임승차      유임하차     무임승차     무임하차\n",
1251:        "호선명                                      \n",
1252:        "1호선   6419075   6270702  2159937  2127650\n",
1253:        "2호선  38115487  38696376  5520166  5455704\n",
1254:        "3호선  13490732  13363899  3268277  3203698\n",
1255:        "4호선  13684728  14001883  3212014  3234665\n",
1256:        "5호선  16337913  16158622  4277487  4209474\n",
1257:        "6호선   8834967   8837115  2046010  2014915\n",
1258:        "7호선  14658705  14416026  3686763  3648071\n",
1259:        "8호선   4946249   5016754  1446371  1416418\n",
1260:        "9호선   7357970   7500446  1404420  1401258"
1261:       ]
1262:      },
1263:      "execution_count": 69,
1264:      "metadata": {},
1265:      "output_type": "execute_result"
1266:     }
1267:    ],
1268:    "source": [
1269:     "sub_pay_graph=sub_pay[['호선명','유임승차','유임하차','무임승차','무임하차']].groupby(by='호선명').sum().head(9)\n",
1270:     "sub_pay_graph"
1271:    ]
1272:   },
1273:   {
1274:    "cell_type": "code",
1275:    "execution_count": 71,
1276:    "id": "9ded5cbc-ebaf-4503-a51e-b2ae96a1bd56",
1277:    "metadata": {},
1278:    "outputs": [
1279:     {
1280:      "data": {
1281:       "image/png": "iVBORw0KGgoAAAANSUhEUgAAAkUAAAHECAYAAAA3el4hAAAAOnRFWHRTb2Z0d2FyZQBNYXRwbG90bGliIHZlcnNpb24zLjEwLjAsIGh0dHBzOi8vbWF0cGxvdGxpYi5vcmcvlHJYcgAAAAlwSFlzAAAPYQAAD2EBqD+naQAAXExJREFUeJzt3XtYVNXCP/DvMMBwERnxHpAgmlBqWSaiZpqhHkMTjyaH4/FeQN4IpNfO6ZSahccLXvCYRJaiQpFveeNIiWmKx0tmhCgoiCgQXkBlMGCAmfX7w9f5Oc4AM1wcGL+f55nnibXWXrM2u+L7rL322hIhhAARERHRY87C1AMgIiIiagkYioiIiIjAUEREREQEgKGIiIiICABDEREREREAhiIiIiIiAAxFRERERAAYiojMVl5eHlJTU/XWqVQq5OTkoKam5hGPqumcOXMGN27cMPUwGuXSpUvIzs429TBapJ9//hl///vf9dYdOHAASUlJj3hE9DhgKCJ6xA4fPgwbG5s62xQXF0MikSAnJ6dBxwPAvn37EBoaqrfu5s2b6NmzJwoKCgwac2N88cUX6N+/v9HHpaamok2bNrXWBwYG4j//+U9jhmawS5cuwdLSEqWlpUYfa2lpidOnT+utW7lyJT7++ONGja2yshISiaTW73iYRCLR+zl27Jim/n5fNjY2OHz4sNFj+s9//gMfH59a60ePHo3FixfX2celS5eQmJiot2737t345ptvjB4XUX0sTT0AInOQl5cHd3f3OttcvnwZbm5uzToOiURSZ1lsbCxmz57dbN9/9+5dndmnP/74A0qlEnfu3NFp7+DgAKlU2mzjaYjKykpUVlZqlSkUCqhUKty5cwcPvwTA1tYWMpnsUQ5Ry969ewEA+/fvNyh83rx5U+vngoIC9OvXr0n/3SwvL0dRUZFRx2zZsgUzZszQKX/w399u3bohLy+vscMjqhVDEVETcHV11fojsGDBAtjY2OBf//qXpqxjx461Hn/nzh2sXbtW83N5eTkAYP369XByctKUv/XWW3WO4/bt25p/3rBhAxITE3HkyBFNmZ2dXf0nU4c7d+4gIiICbdq0wZo1a3TqX331VZw8eVLvse3atdMpO378OAYOHKi3fWVlJZRKJdRqNSwsGj+prVarERUVhU2bNuHq1atwdXXFO++8g7lz52q1W7x4sdZ1e5C+4BAZGYlFixbpbV9dXQ2VSqW5nk3tyJEjeOutt/DBBx9g3bp1eOqppzB58uQ6j+nQoYPWz8nJyXB3d4ezs3ODx/HDDz9o/btZXl6OW7duaf2+XFxcar2dC9yb+Rs/fnyd39MU/x4Q1YWhiKgJSKVSdOnSRfOzTCaDtbW1VlldVCoVrl27plUWFBSEqqoqrfL61gDJ5XLNP1+6dAm5ubmwsrKCvb09rl+/jg0bNgC4N6NjjKKiImzevBlr167FnTt3dILEfSdOnNApE0JApVLB0tK4/92kp6ejpqYGv/76K1544QVs2bIFmzZt0tRfuXLFqP4iIiIQFxeHqKgo9OvXD4cPH8a7774LW1tbzJo1S9Nu+fLlWL58uc7xNTU1Rp/D2bNnAdxbHzN06FCkp6drhYfLly/jT3/6k1F9AkB+fj5Wr16Nbdu24dNPP0VAQAD8/PwQGBiIffv24f3330evXr0M6mvTpk2YPn26Vtm+ffuQkZEBlUplUB/e3t7YtWuXVpkQQmuWx9raus4+rK2tIYTAqlWr8M033yAvLw9KpRIdOnTA0KFD8e677+LZZ581aDxEDcVQRNQMiouLjbql0r59e60/+JWVlcjPz4ezs7PO7E5ubm69/d1fj+Hi4oIPPvgAq1evRnl5uSa0KJVKg8cGADExMdi+fTtWrFiBuLi4etufOXMGUVFR+Omnn1BYWAghBBwcHNCnTx/89a9/xVtvvVVvwNi2bRu6du2KtWvXYtu2bRgwYIDWWqrw8HCDx19SUoL169cj... (line truncated to 2000 chars)
1282:       "text/plain": [
1283:        "<Figure size 640x480 with 1 Axes>"
1284:       ]
1285:      },
1286:      "metadata": {},
1287:      "output_type": "display_data"
1288:     }
1289:    ],
1290:    "source": [
1291:     "sub_pay_graph.plot(kind='barh', rot=0)   # bar는 익히 아는 그 세로의 바, bar'h'는 수평 막대\n",
1292:     "\n",
1293:     "plt.title('지하철 1호선-9호선 승객 현황')\n",
1294:     "plt.xlabel('호선명', loc='right')\n",
1295:     "plt.ylabel('인원(명)', loc='top')\n",
1296:     "plt.show()"
1297:    ]
1298:   },
1299:   {
1300:    "cell_type": "code",
1301:    "execution_count": 77,
1302:    "id": "85b9ae7c-9cdb-4da1-a451-07ed48afea70",
1303:    "metadata": {},
1304:    "outputs": [],
1305:    "source": [
1306:     "# 여기 아래부터는... 음..."
1307:    ]
1308:   },
1309:   {
1310:    "cell_type": "code",
1311:    "execution_count": 74,
1312:    "id": "d445a2c3-d576-47c6-ab92-37261ea52ac9",
1313:    "metadata": {},
1314:    "outputs": [
1315:     {
1316:      "ename": "KeyError",
1317:      "evalue": "\"None of [Index(['경인선', '경의선', '경원선', '경부선', '경강선'], dtype='object')] are in the [columns]\"",
1318:      "output_type": "error",
1319:      "traceback": [
1320:       "\u001b[1;31m---------------------------------------------------------------------------\u001b[0m",
1321:       "\u001b[1;31mKeyError\u001b[0m                                  Traceback (most recent call last)",
1322:       "Cell \u001b[1;32mIn[74], line 1\u001b[0m\n\u001b[1;32m----> 1\u001b[0m sub_pay_graph_init_okay\u001b[38;5;241m=\u001b[39msub_pay_graph2_init\u001b[38;5;241m=\u001b[39msub_pay[[\u001b[38;5;124m'\u001b[39m\u001b[38;5;124m경인선\u001b[39m\u001b[38;5;124m'\u001b[39m,\u001b[38;5;124m'\u001b[39m\u001b[38;5;124m경의선\u001b[39m\u001b[38;5;124m'\u001b[39m,\u001b[38;5;124m'\u001b[39m\u001b[38;5;124m경원선\u001b[39m\u001b[38;5;124m'\u001b[39m,\u001b[38;5;124m'\u001b[39m\u001b[38;5;124m경부선\u001b[39m\u001b[38;5;124m'\u001b[39m,\u001b[38;5;124m'\u001b[39m\u001b[38;5;124m경강선\u001b[39m\u001b[38;5;124m'\u001b[39m]]\n\u001b[0;32m      2\u001b[0m sub_pay_graph_init_okay\n",
1323:       "File \u001b[1;32mC:\\ProgramData\\anaconda3\\Lib\\site-packages\\pandas\\core\\frame.py:4108\u001b[0m, in \u001b[0;36mDataFrame.__getitem__\u001b[1;34m(self, key)\u001b[0m\n\u001b[0;32m   4106\u001b[0m     \u001b[38;5;28;01mif\u001b[39;00m is_iterator(key):\n\u001b[0;32m   4107\u001b[0m         key \u001b[38;5;241m=\u001b[39m \u001b[38;5;28mlist\u001b[39m(key)\n\u001b[1;32m-> 4108\u001b[0m     indexer \u001b[38;5;241m=\u001b[39m \u001b[38;5;28mself\u001b[39m\u001b[38;5;241m.\u001b[39mcolumns\u001b[38;5;241m.\u001b[39m_get_indexer_strict(key, \u001b[38;5;124m\"\u001b[39m\u001b[38;5;124mcolumns\u001b[39m\u001b[38;5;124m\"\u001b[39m)[\u001b[38;5;241m1\u001b[39m]\n\u001b[0;32m   4110\u001b[0m \u001b[38;5;66;03m# take() does not accept boolean indexers\u001b[39;00m\n\u001b[0;32m   4111\u001b[0m \u001b[38;5;28;01mif\u001b[39;00m \u001b[38;5;28mgetattr\u001b[39m(indexer, \u001b[38;5;124m\"\u001b[39m\u001b[38;5;124mdtype\u001b[39m\u001b[38;5;124m\"\u001b[39m, \u001b[38;5;28;01mNone\u001b[39;00m) \u001b[38;5;241m==\u001b[39m \u001b[38;5;28mbool\u001b[39m:\n",
1324:       "File \u001b[1;32mC:\\ProgramData\\anaconda3\\Lib\\site-packages\\pandas\\core\\indexes\\base.py:6200\u001b[0m, in \u001b[0;36mIndex._get_indexer_strict\u001b[1;34m(self, key, axis_name)\u001b[0m\n\u001b[0;32m   6197\u001b[0m \u001b[38;5;28;01melse\u001b[39;00m:\n\u001b[0;32m   6198\u001b[0m     keyarr, indexer, new_indexer \u001b[38;5;241m=\u001b[39m \u001b[38;5;28mself\u001b[39m\u001b[38;5;241m.\u001b[39m_reindex_non_unique(keyarr)\n\u001b[1;32m-> 6200\u001b[0m \u001b[38;5;28mself\u001b[39m\u001b[38;5;241m.\u001b[39m_raise_if_missing(keyarr, indexer, axis_name)\n\u001b[0;32m   6202\u001b[0m keyarr \u001b[38;5;241m=\u001b[39m \u001b[38;5;28mself\u001b[39m\u001b[38;5;241m.\u001b[39mtake(indexer)\n\u001b[0;32m   6203\u001b[0m \u001b[38;5;28;01mif\u001b[39;00m \u001b[38;5;28misinstance\u001b[39m(key, Index):\n\u001b[0;32m   6204\u001b[0m     \u001b[38;5;66;03m# GH 42790 - Preserve name from an Index\u001b[39;00m\n",

(Output capped at 50 KB. Showing lines 1-1324. Use offset=1325 to continue.)
</content>
```

**Tool: read**

**Input:**
```json
{
  "filePath": "C:\\Users\\Administrator\\Documents\\GitHub\\kw-competition-practice\\20260705-일요실습1.md"
}
```

**Output:**
```
<path>C:\Users\Administrator\Documents\GitHub\kw-competition-practice\20260705-일요실습1.md</path>
<type>file</type>
<content>
1: # **20260705-일요실습1**
2: 
3: ### 시작 - 
4: 
5: 
6: ```python
7: 
8: ```

(End of file - total 8 lines)
</content>
```

**Tool: read**

**Input:**
```json
{
  "filePath": "C:\\Users\\Administrator\\Documents\\GitHub\\kw-competition-practice\\20260719-일요실습1.ipynb"
}
```

**Output:**
```
<path>C:\Users\Administrator\Documents\GitHub\kw-competition-practice\20260719-일요실습1.ipynb</path>
<type>file</type>
<content>
1: {
2:  "cells": [
3:   {
4:    "cell_type": "markdown",
5:    "id": "da038d0d-24b2-4142-b671-105493364a05",
6:    "metadata": {},
7:    "source": [
8:     "# **20260704-토요실습1** (사실 0704 토요실습 파일 그대로 복사된것...) (오늘이 19인데 별로 안했단 것...)"
9:    ]
10:   },
11:   {
12:    "cell_type": "markdown",
13:    "id": "6f2d32c7-bcb2-4dfd-9c3d-3764e22d84f3",
14:    "metadata": {},
15:    "source": [
16:     "### 먼저 전체를 출력"
17:    ]
18:   },
19:   {
20:    "cell_type": "code",
21:    "execution_count": 1,
22:    "id": "b530408c-be72-4b41-b44a-05ec0d0a1247",
23:    "metadata": {},
24:    "outputs": [
25:     {
26:      "data": {
27:       "text/html": [
28:        "<div>\n",
29:        "<style scoped>\n",
30:        "    .dataframe tbody tr th:only-of-type {\n",
31:        "        vertical-align: middle;\n",
32:        "    }\n",
33:        "\n",
34:        "    .dataframe tbody tr th {\n",
35:        "        vertical-align: top;\n",
36:        "    }\n",
37:        "\n",
38:        "    .dataframe thead th {\n",
39:        "        text-align: right;\n",
40:        "    }\n",
41:        "</style>\n",
42:        "<table border=\"1\" class=\"dataframe\">\n",
43:        "  <thead>\n",
44:        "    <tr style=\"text-align: right;\">\n",
45:        "      <th></th>\n",
46:        "      <th>사용월</th>\n",
47:        "      <th>노선ID</th>\n",
48:        "      <th>노선번호</th>\n",
49:        "      <th>노선명</th>\n",
50:        "      <th>버스정류장ID</th>\n",
51:        "      <th>버스정류장명</th>\n",
52:        "      <th>승차승객수</th>\n",
53:        "      <th>하차승객수</th>\n",
54:        "      <th>작업일시</th>\n",
55:        "    </tr>\n",
56:        "  </thead>\n",
57:        "  <tbody>\n",
58:        "    <tr>\n",
59:        "      <th>0</th>\n",
60:        "      <td>2026-05</td>\n",
61:        "      <td>11110897</td>\n",
62:        "      <td>17</td>\n",
63:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
64:        "      <td>8503228</td>\n",
65:        "      <td>용산차고지(가상)</td>\n",
66:        "      <td>25</td>\n",
67:        "      <td>5</td>\n",
68:        "      <td>2026-06-03 10:00:24</td>\n",
69:        "    </tr>\n",
70:        "    <tr>\n",
71:        "      <th>1</th>\n",
72:        "      <td>2026-05</td>\n",
73:        "      <td>11110897</td>\n",
74:        "      <td>17</td>\n",
75:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
76:        "      <td>8503189</td>\n",
77:        "      <td>신용산지하차도</td>\n",
78:        "      <td>735</td>\n",
79:        "      <td>21</td>\n",
80:        "      <td>2026-06-03 10:00:24</td>\n",
81:        "    </tr>\n",
82:        "    <tr>\n",
83:        "      <th>2</th>\n",
84:        "      <td>2026-05</td>\n",
85:        "      <td>11110897</td>\n",
86:        "      <td>17</td>\n",
87:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
88:        "      <td>72992</td>\n",
89:        "      <td>용산역</td>\n",
90:        "      <td>22519</td>\n",
91:        "      <td>352</td>\n",
92:        "      <td>2026-06-03 10:00:24</td>\n",
93:        "    </tr>\n",
94:        "    <tr>\n",
95:        "      <th>3</th>\n",
96:        "      <td>2026-05</td>\n",
97:        "      <td>11110897</td>\n",
98:        "      <td>17</td>\n",
99:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
100:        "      <td>72314</td>\n",
101:        "      <td>용산푸르지오써밋</td>\n",
102:        "      <td>1782</td>\n",
103:        "      <td>488</td>\n",
104:        "      <td>2026-06-03 10:00:24</td>\n",
105:        "    </tr>\n",
106:        "    <tr>\n",
107:        "      <th>4</th>\n",
108:        "      <td>2026-05</td>\n",
109:        "      <td>11110897</td>\n",
110:        "      <td>17</td>\n",
111:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
112:        "      <td>72993</td>\n",
113:        "      <td>한강대교북단</td>\n",
114:        "      <td>7261</td>\n",
115:        "      <td>1998</td>\n",
116:        "      <td>2026-06-03 10:00:24</td>\n",
117:        "    </tr>\n",
118:        "    <tr>\n",
119:        "      <th>...</th>\n",
120:        "      <td>...</td>\n",
121:        "      <td>...</td>\n",
122:        "      <td>...</td>\n",
123:        "      <td>...</td>\n",
124:        "      <td>...</td>\n",
125:        "      <td>...</td>\n",
126:        "      <td>...</td>\n",
127:        "      <td>...</td>\n",
128:        "      <td>...</td>\n",
129:        "    </tr>\n",
130:        "    <tr>\n",
131:        "      <th>41995</th>\n",
132:        "      <td>2026-05</td>\n",
133:        "      <td>92000001</td>\n",
134:        "      <td>한강버스01</td>\n",
135:        "      <td>한강버스01(마곡~잠실)</td>\n",
136:        "      <td>8503213</td>\n",
137:        "      <td>압구정</td>\n",
138:        "      <td>4899</td>\n",
139:        "      <td>3375</td>\n",
140:        "      <td>2026-06-03 10:00:24</td>\n",
141:        "    </tr>\n",
142:        "    <tr>\n",
143:        "      <th>41996</th>\n",
144:        "      <td>2026-05</td>\n",
145:        "      <td>92000001</td>\n",
146:        "      <td>한강버스01</td>\n",
147:        "      <td>한강버스01(마곡~잠실)</td>\n",
148:        "      <td>8503214</td>\n",
149:        "      <td>옥수</td>\n",
150:        "      <td>5891</td>\n",
151:        "      <td>3566</td>\n",
152:        "      <td>2026-06-03 10:00:24</td>\n",
153:        "    </tr>\n",
154:        "    <tr>\n",
155:        "      <th>41997</th>\n",
156:        "      <td>2026-05</td>\n",
157:        "      <td>92000001</td>\n",
158:        "      <td>한강버스01</td>\n",
159:        "      <td>한강버스01(마곡~잠실)</td>\n",
160:        "      <td>8503414</td>\n",
161:        "      <td>성수</td>\n",
162:        "      <td>4</td>\n",
163:        "      <td>4</td>\n",
164:        "      <td>2026-06-03 10:00:24</td>\n",
165:        "    </tr>\n",
166:        "    <tr>\n",
167:        "      <th>41998</th>\n",
168:        "      <td>2026-05</td>\n",
169:        "      <td>92000001</td>\n",
170:        "      <td>한강버스01</td>\n",
171:        "      <td>한강버스01(마곡~잠실)</td>\n",
172:        "      <td>8503215</td>\n",
173:        "      <td>뚝섬</td>\n",
174:        "      <td>8736</td>\n",
175:        "      <td>6459</td>\n",
176:        "      <td>2026-06-03 10:00:24</td>\n",
177:        "    </tr>\n",
178:        "    <tr>\n",
179:        "      <th>41999</th>\n",
180:        "      <td>2026-05</td>\n",
181:        "      <td>92000001</td>\n",
182:        "      <td>한강버스01</td>\n",
183:        "      <td>한강버스01(마곡~잠실)</td>\n",
184:        "      <td>8503216</td>\n",
185:        "      <td>잠실</td>\n",
186:        "      <td>9667</td>\n",
187:        "      <td>12434</td>\n",
188:        "      <td>2026-06-03 10:00:24</td>\n",
189:        "    </tr>\n",
190:        "  </tbody>\n",
191:        "</table>\n",
192:        "<p>42000 rows × 9 columns</p>\n",
193:        "</div>"
194:       ],
195:       "text/plain": [
196:        "           사용월      노선ID    노선번호                    노선명  버스정류장ID     버스정류장명  \\\n",
197:        "0      2026-05  11110897      17  0017번(용산차고지~신용산역3번출구)  8503228  용산차고지(가상)   \n",
198:        "1      2026-05  11110897      17  0017번(용산차고지~신용산역3번출구)  8503189    신용산지하차도   \n",
199:        "2      2026-05  11110897      17  0017번(용산차고지~신용산역3번출구)    72992        용산역   \n",
200:        "3      2026-05  11110897      17  0017번(용산차고지~신용산역3번출구)    72314   용산푸르지오써밋   \n",
201:        "4      2026-05  11110897      17  0017번(용산차고지~신용산역3번출구)    72993     한강대교북단   \n",
202:        "...        ...       ...     ...                    ...      ...        ...   \n",
203:        "41995  2026-05  92000001  한강버스01          한강버스01(마곡~잠실)  8503213        압구정   \n",
204:        "41996  2026-05  92000001  한강버스01          한강버스01(마곡~잠실)  8503214         옥수   \n",
205:        "41997  2026-05  92000001  한강버스01          한강버스01(마곡~잠실)  8503414         성수   \n",
206:        "41998  2026-05  92000001  한강버스01          한강버스01(마곡~잠실)  8503215         뚝섬   \n",
207:        "41999  2026-05  92000001  한강버스01          한강버스01(마곡~잠실)  8503216         잠실   \n",
208:        "\n",
209:        "       승차승객수  하차승객수                작업일시  \n",
210:        "0         25      5 2026-06-03 10:00:24  \n",
211:        "1        735     21 2026-06-03 10:00:24  \n",
212:        "2      22519    352 2026-06-03 10:00:24  \n",
213:        "3       1782    488 2026-06-03 10:00:24  \n",
214:        "4       7261   1998 2026-06-03 10:00:24  \n",
215:        "...      ...    ...                 ...  \n",
216:        "41995   4899   3375 2026-06-03 10:00:24  \n",
217:        "41996   5891   3566 2026-06-03 10:00:24  \n",
218:        "41997      4      4 2026-06-03 10:00:24  \n",
219:        "41998   8736   6459 2026-06-03 10:00:24  \n",
220:        "41999   9667  12434 2026-06-03 10:00:24  \n",
221:        "\n",
222:        "[42000 rows x 9 columns]"
223:       ]
224:      },
225:      "execution_count": 1,
226:      "metadata": {},
227:      "output_type": "execute_result"
228:     }
229:    ],
230:    "source": [
231:     "import matplotlib.pyplot as plt\n",
232:     "import pandas as pd\n",
233:     "import numpy as np\n",
234:     "\n",
235:     "bus_station=pd.read_excel('seoul_traffic_202605.xlsx', sheet_name='bus_station')\n",
236:     "bus_station"
237:    ]
238:   },
239:   {
240:    "cell_type": "code",
241:    "execution_count": null,
242:    "id": "8caf9f3c-157d-4757-876e-d7f9c9daf2b5",
243:    "metadata": {},
244:    "outputs": [],
245:    "source": []
246:   },
247:   {
248:    "cell_type": "markdown",
249:    "id": "27b34e4c-4e0e-4d30-a1e6-7455dc5f17bb",
250:    "metadata": {},
251:    "source": [
252:     "### 선택 출력"
253:    ]
254:   },
255:   {
256:    "cell_type": "code",
257:    "execution_count": 99,
258:    "id": "275fc5e8-9af3-41ed-b74c-1116dc04e7c4",
259:    "metadata": {},
260:    "outputs": [
261:     {
262:      "data": {
263:       "text/html": [
264:        "<div>\n",
265:        "<style scoped>\n",
266:        "    .dataframe tbody tr th:only-of-type {\n",
267:        "        vertical-align: middle;\n",
268:        "    }\n",
269:        "\n",
270:        "    .dataframe tbody tr th {\n",
271:        "        vertical-align: top;\n",
272:        "    }\n",
273:        "\n",
274:        "    .dataframe thead th {\n",
275:        "        text-align: right;\n",
276:        "    }\n",
277:        "</style>\n",
278:        "<table border=\"1\" class=\"dataframe\">\n",
279:        "  <thead>\n",
280:        "    <tr style=\"text-align: right;\">\n",
281:        "      <th></th>\n",
282:        "      <th>버스정류장ID</th>\n",
283:        "      <th>승차승객수</th>\n",
284:        "    </tr>\n",
285:        "  </thead>\n",
286:        "  <tbody>\n",
287:        "    <tr>\n",
288:        "      <th>0</th>\n",
289:        "      <td>8503228</td>\n",
290:        "      <td>25</td>\n",
291:        "    </tr>\n",
292:        "    <tr>\n",
293:        "      <th>1</th>\n",
294:        "      <td>8503189</td>\n",
295:        "      <td>735</td>\n",
296:        "    </tr>\n",
297:        "    <tr>\n",
298:        "      <th>2</th>\n",
299:        "      <td>72992</td>\n",
300:        "      <td>22519</td>\n",
301:        "    </tr>\n",
302:        "    <tr>\n",
303:        "      <th>3</th>\n",
304:        "      <td>72314</td>\n",
305:        "      <td>1782</td>\n",
306:        "    </tr>\n",
307:        "    <tr>\n",
308:        "      <th>4</th>\n",
309:        "      <td>72993</td>\n",
310:        "      <td>7261</td>\n",
311:        "    </tr>\n",
312:        "    <tr>\n",
313:        "      <th>...</th>\n",
314:        "      <td>...</td>\n",
315:        "      <td>...</td>\n",
316:        "    </tr>\n",
317:        "    <tr>\n",
318:        "      <th>41995</th>\n",
319:        "      <td>8503213</td>\n",
320:        "      <td>4899</td>\n",
321:        "    </tr>\n",
322:        "    <tr>\n",
323:        "      <th>41996</th>\n",
324:        "      <td>8503214</td>\n",
325:        "      <td>5891</td>\n",
326:        "    </tr>\n",
327:        "    <tr>\n",
328:        "      <th>41997</th>\n",
329:        "      <td>8503414</td>\n",
330:        "      <td>4</td>\n",
331:        "    </tr>\n",
332:        "    <tr>\n",
333:        "      <th>41998</th>\n",
334:        "      <td>8503215</td>\n",
335:        "      <td>8736</td>\n",
336:        "    </tr>\n",
337:        "    <tr>\n",
338:        "      <th>41999</th>\n",
339:        "      <td>8503216</td>\n",
340:        "      <td>9667</td>\n",
341:        "    </tr>\n",
342:        "  </tbody>\n",
343:        "</table>\n",
344:        "<p>42000 rows × 2 columns</p>\n",
345:        "</div>"
346:       ],
347:       "text/plain": [
348:        "       버스정류장ID  승차승객수\n",
349:        "0      8503228     25\n",
350:        "1      8503189    735\n",
351:        "2        72992  22519\n",
352:        "3        72314   1782\n",
353:        "4        72993   7261\n",
354:        "...        ...    ...\n",
355:        "41995  8503213   4899\n",
356:        "41996  8503214   5891\n",
357:        "41997  8503414      4\n",
358:        "41998  8503215   8736\n",
359:        "41999  8503216   9667\n",
360:        "\n",
361:        "[42000 rows x 2 columns]"
362:       ]
363:      },
364:      "execution_count": 99,
365:      "metadata": {},
366:      "output_type": "execute_result"
367:     }
368:    ],
369:    "source": [
370:     "bus_station[['버스정류장ID', '승차승객수']] # 두 가지 열만 선택"
371:    ]
372:   },
373:   {
374:    "cell_type": "code",
375:    "execution_count": 100,
376:    "id": "8ed254f1-118d-48da-ba7a-a7d6a438fd23",
377:    "metadata": {},
378:    "outputs": [
379:     {
380:      "data": {
381:       "text/html": [
382:        "<div>\n",
383:        "<style scoped>\n",
384:        "    .dataframe tbody tr th:only-of-type {\n",
385:        "        vertical-align: middle;\n",
386:        "    }\n",
387:        "\n",
388:        "    .dataframe tbody tr th {\n",
389:        "        vertical-align: top;\n",
390:        "    }\n",
391:        "\n",
392:        "    .dataframe thead th {\n",
393:        "        text-align: right;\n",
394:        "    }\n",
395:        "</style>\n",
396:        "<table border=\"1\" class=\"dataframe\">\n",
397:        "  <thead>\n",
398:        "    <tr style=\"text-align: right;\">\n",
399:        "      <th></th>\n",
400:        "      <th>노선번호</th>\n",
401:        "      <th>노선명</th>\n",
402:        "    </tr>\n",
403:        "  </thead>\n",
404:        "  <tbody>\n",
405:        "    <tr>\n",
406:        "      <th>0</th>\n",
407:        "      <td>17</td>\n",
408:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
409:        "    </tr>\n",
410:        "    <tr>\n",
411:        "      <th>1</th>\n",
412:        "      <td>17</td>\n",
413:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
414:        "    </tr>\n",
415:        "    <tr>\n",
416:        "      <th>2</th>\n",
417:        "      <td>17</td>\n",
418:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
419:        "    </tr>\n",
420:        "    <tr>\n",
421:        "      <th>3</th>\n",
422:        "      <td>17</td>\n",
423:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
424:        "    </tr>\n",
425:        "    <tr>\n",
426:        "      <th>4</th>\n",
427:        "      <td>17</td>\n",
428:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
429:        "    </tr>\n",
430:        "    <tr>\n",
431:        "      <th>...</th>\n",
432:        "      <td>...</td>\n",
433:        "      <td>...</td>\n",
434:        "    </tr>\n",
435:        "    <tr>\n",
436:        "      <th>41995</th>\n",
437:        "      <td>한강버스01</td>\n",
438:        "      <td>한강버스01(마곡~잠실)</td>\n",
439:        "    </tr>\n",
440:        "    <tr>\n",
441:        "      <th>41996</th>\n",
442:        "      <td>한강버스01</td>\n",
443:        "      <td>한강버스01(마곡~잠실)</td>\n",
444:        "    </tr>\n",
445:        "    <tr>\n",
446:        "      <th>41997</th>\n",
447:        "      <td>한강버스01</td>\n",
448:        "      <td>한강버스01(마곡~잠실)</td>\n",
449:        "    </tr>\n",
450:        "    <tr>\n",
451:        "      <th>41998</th>\n",
452:        "      <td>한강버스01</td>\n",
453:        "      <td>한강버스01(마곡~잠실)</td>\n",
454:        "    </tr>\n",
455:        "    <tr>\n",
456:        "      <th>41999</th>\n",
457:        "      <td>한강버스01</td>\n",
458:        "      <td>한강버스01(마곡~잠실)</td>\n",
459:        "    </tr>\n",
460:        "  </tbody>\n",
461:        "</table>\n",
462:        "<p>42000 rows × 2 columns</p>\n",
463:        "</div>"
464:       ],
465:       "text/plain": [
466:        "         노선번호                    노선명\n",
467:        "0          17  0017번(용산차고지~신용산역3번출구)\n",
468:        "1          17  0017번(용산차고지~신용산역3번출구)\n",
469:        "2          17  0017번(용산차고지~신용산역3번출구)\n",
470:        "3          17  0017번(용산차고지~신용산역3번출구)\n",
471:        "4          17  0017번(용산차고지~신용산역3번출구)\n",
472:        "...       ...                    ...\n",
473:        "41995  한강버스01          한강버스01(마곡~잠실)\n",
474:        "41996  한강버스01          한강버스01(마곡~잠실)\n",
475:        "41997  한강버스01          한강버스01(마곡~잠실)\n",
476:        "41998  한강버스01          한강버스01(마곡~잠실)\n",
477:        "41999  한강버스01          한강버스01(마곡~잠실)\n",
478:        "\n",
479:        "[42000 rows x 2 columns]"
480:       ]
481:      },
482:      "execution_count": 100,
483:      "metadata": {},
484:      "output_type": "execute_result"
485:     }
486:    ],
487:    "source": [
488:     "bus_station[['노선번호', '노선명']] # 두 가지 열만 선택"
489:    ]
490:   },
491:   {
492:    "cell_type": "code",
493:    "execution_count": 101,
494:    "id": "ae0817ce-4b8c-43bc-9cba-87d3d91a6901",
495:    "metadata": {},
496:    "outputs": [
497:     {
498:      "data": {
499:       "text/html": [
500:        "<div>\n",
501:        "<style scoped>\n",
502:        "    .dataframe tbody tr th:only-of-type {\n",
503:        "        vertical-align: middle;\n",
504:        "    }\n",
505:        "\n",
506:        "    .dataframe tbody tr th {\n",
507:        "        vertical-align: top;\n",
508:        "    }\n",
509:        "\n",
510:        "    .dataframe thead th {\n",
511:        "        text-align: right;\n",
512:        "    }\n",
513:        "</style>\n",
514:        "<table border=\"1\" class=\"dataframe\">\n",
515:        "  <thead>\n",
516:        "    <tr style=\"text-align: right;\">\n",
517:        "      <th></th>\n",
518:        "      <th>노선번호</th>\n",
519:        "      <th>노선명</th>\n",
520:        "      <th>버스정류장ID</th>\n",
521:        "      <th>버스정류장명</th>\n",
522:        "      <th>승차승객수</th>\n",
523:        "      <th>하차승객수</th>\n",
524:        "    </tr>\n",
525:        "  </thead>\n",
526:        "  <tbody>\n",
527:        "    <tr>\n",
528:        "      <th>0</th>\n",
529:        "      <td>17</td>\n",
530:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
531:        "      <td>8503228</td>\n",
532:        "      <td>용산차고지(가상)</td>\n",
533:        "      <td>25</td>\n",
534:        "      <td>5</td>\n",
535:        "    </tr>\n",
536:        "    <tr>\n",
537:        "      <th>1</th>\n",
538:        "      <td>17</td>\n",
539:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
540:        "      <td>8503189</td>\n",
541:        "      <td>신용산지하차도</td>\n",
542:        "      <td>735</td>\n",
543:        "      <td>21</td>\n",
544:        "    </tr>\n",
545:        "    <tr>\n",
546:        "      <th>2</th>\n",
547:        "      <td>17</td>\n",
548:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
549:        "      <td>72992</td>\n",
550:        "      <td>용산역</td>\n",
551:        "      <td>22519</td>\n",
552:        "      <td>352</td>\n",
553:        "    </tr>\n",
554:        "    <tr>\n",
555:        "      <th>3</th>\n",
556:        "      <td>17</td>\n",
557:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
558:        "      <td>72314</td>\n",
559:        "      <td>용산푸르지오써밋</td>\n",
560:        "      <td>1782</td>\n",
561:        "      <td>488</td>\n",
562:        "    </tr>\n",
563:        "    <tr>\n",
564:        "      <th>4</th>\n",
565:        "      <td>17</td>\n",
566:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
567:        "      <td>72993</td>\n",
568:        "      <td>한강대교북단</td>\n",
569:        "      <td>7261</td>\n",
570:        "      <td>1998</td>\n",
571:        "    </tr>\n",
572:        "    <tr>\n",
573:        "      <th>...</th>\n",
574:        "      <td>...</td>\n",
575:        "      <td>...</td>\n",
576:        "      <td>...</td>\n",
577:        "      <td>...</td>\n",
578:        "      <td>...</td>\n",
579:        "      <td>...</td>\n",
580:        "    </tr>\n",
581:        "    <tr>\n",
582:        "      <th>41995</th>\n",
583:        "      <td>한강버스01</td>\n",
584:        "      <td>한강버스01(마곡~잠실)</td>\n",
585:        "      <td>8503213</td>\n",
586:        "      <td>압구정</td>\n",
587:        "      <td>4899</td>\n",
588:        "      <td>3375</td>\n",
589:        "    </tr>\n",
590:        "    <tr>\n",
591:        "      <th>41996</th>\n",
592:        "      <td>한강버스01</td>\n",
593:        "      <td>한강버스01(마곡~잠실)</td>\n",
594:        "      <td>8503214</td>\n",
595:        "      <td>옥수</td>\n",
596:        "      <td>5891</td>\n",
597:        "      <td>3566</td>\n",
598:        "    </tr>\n",
599:        "    <tr>\n",
600:        "      <th>41997</th>\n",
601:        "      <td>한강버스01</td>\n",
602:        "      <td>한강버스01(마곡~잠실)</td>\n",
603:        "      <td>8503414</td>\n",
604:        "      <td>성수</td>\n",
605:        "      <td>4</td>\n",
606:        "      <td>4</td>\n",
607:        "    </tr>\n",
608:        "    <tr>\n",
609:        "      <th>41998</th>\n",
610:        "      <td>한강버스01</td>\n",
611:        "      <td>한강버스01(마곡~잠실)</td>\n",
612:        "      <td>8503215</td>\n",
613:        "      <td>뚝섬</td>\n",
614:        "      <td>8736</td>\n",
615:        "      <td>6459</td>\n",
616:        "    </tr>\n",
617:        "    <tr>\n",
618:        "      <th>41999</th>\n",
619:        "      <td>한강버스01</td>\n",
620:        "      <td>한강버스01(마곡~잠실)</td>\n",
621:        "      <td>8503216</td>\n",
622:        "      <td>잠실</td>\n",
623:        "      <td>9667</td>\n",
624:        "      <td>12434</td>\n",
625:        "    </tr>\n",
626:        "  </tbody>\n",
627:        "</table>\n",
628:        "<p>42000 rows × 6 columns</p>\n",
629:        "</div>"
630:       ],
631:       "text/plain": [
632:        "         노선번호                    노선명  버스정류장ID     버스정류장명  승차승객수  하차승객수\n",
633:        "0          17  0017번(용산차고지~신용산역3번출구)  8503228  용산차고지(가상)     25      5\n",
634:        "1          17  0017번(용산차고지~신용산역3번출구)  8503189    신용산지하차도    735     21\n",
635:        "2          17  0017번(용산차고지~신용산역3번출구)    72992        용산역  22519    352\n",
636:        "3          17  0017번(용산차고지~신용산역3번출구)    72314   용산푸르지오써밋   1782    488\n",
637:        "4          17  0017번(용산차고지~신용산역3번출구)    72993     한강대교북단   7261   1998\n",
638:        "...       ...                    ...      ...        ...    ...    ...\n",
639:        "41995  한강버스01          한강버스01(마곡~잠실)  8503213        압구정   4899   3375\n",
640:        "41996  한강버스01          한강버스01(마곡~잠실)  8503214         옥수   5891   3566\n",
641:        "41997  한강버스01          한강버스01(마곡~잠실)  8503414         성수      4      4\n",
642:        "41998  한강버스01          한강버스01(마곡~잠실)  8503215         뚝섬   8736   6459\n",
643:        "41999  한강버스01          한강버스01(마곡~잠실)  8503216         잠실   9667  12434\n",
644:        "\n",
645:        "[42000 rows x 6 columns]"
646:       ]
647:      },
648:      "execution_count": 101,
649:      "metadata": {},
650:      "output_type": "execute_result"
651:     }
652:    ],
653:    "source": [
654:     "bus_station[['노선번호','노선명','버스정류장ID','버스정류장명','승차승객수','하차승객수']] # 출력하고픈 열들을 지정"
655:    ]
656:   },
657:   {
658:    "cell_type": "code",
659:    "execution_count": 102,
660:    "id": "74d45ad3-e1cb-4f7c-a01d-3924a0a2b891",
661:    "metadata": {},
662:    "outputs": [
663:     {
664:      "data": {
665:       "text/html": [
666:        "<div>\n",
667:        "<style scoped>\n",
668:        "    .dataframe tbody tr th:only-of-type {\n",
669:        "        vertical-align: middle;\n",
670:        "    }\n",
671:        "\n",
672:        "    .dataframe tbody tr th {\n",
673:        "        vertical-align: top;\n",
674:        "    }\n",
675:        "\n",
676:        "    .dataframe thead th {\n",
677:        "        text-align: right;\n",
678:        "    }\n",
679:        "</style>\n",
680:        "<table border=\"1\" class=\"dataframe\">\n",
681:        "  <thead>\n",
682:        "    <tr style=\"text-align: right;\">\n",
683:        "      <th></th>\n",
684:        "      <th>노선번호</th>\n",
685:        "      <th>노선명</th>\n",
686:        "      <th>버스정류장ID</th>\n",
687:        "      <th>버스정류장명</th>\n",
688:        "      <th>승차승객수</th>\n",
689:        "      <th>하차승객수</th>\n",
690:        "    </tr>\n",
691:        "  </thead>\n",
692:        "  <tbody>\n",
693:        "    <tr>\n",
694:        "      <th>0</th>\n",
695:        "      <td>17</td>\n",
696:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
697:        "      <td>8503228</td>\n",
698:        "      <td>용산차고지(가상)</td>\n",
699:        "      <td>25</td>\n",
700:        "      <td>5</td>\n",
701:        "    </tr>\n",
702:        "    <tr>\n",
703:        "      <th>1</th>\n",
704:        "      <td>17</td>\n",
705:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
706:        "      <td>8503189</td>\n",
707:        "      <td>신용산지하차도</td>\n",
708:        "      <td>735</td>\n",
709:        "      <td>21</td>\n",
710:        "    </tr>\n",
711:        "    <tr>\n",
712:        "      <th>2</th>\n",
713:        "      <td>17</td>\n",
714:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
715:        "      <td>72992</td>\n",
716:        "      <td>용산역</td>\n",
717:        "      <td>22519</td>\n",
718:        "      <td>352</td>\n",
719:        "    </tr>\n",
720:        "    <tr>\n",
721:        "      <th>3</th>\n",
722:        "      <td>17</td>\n",
723:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
724:        "      <td>72314</td>\n",
725:        "      <td>용산푸르지오써밋</td>\n",
726:        "      <td>1782</td>\n",
727:        "      <td>488</td>\n",
728:        "    </tr>\n",
729:        "    <tr>\n",
730:        "      <th>4</th>\n",
731:        "      <td>17</td>\n",
732:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
733:        "      <td>72993</td>\n",
734:        "      <td>한강대교북단</td>\n",
735:        "      <td>7261</td>\n",
736:        "      <td>1998</td>\n",
737:        "    </tr>\n",
738:        "    <tr>\n",
739:        "      <th>5</th>\n",
740:        "      <td>17</td>\n",
741:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
742:        "      <td>72994</td>\n",
743:        "      <td>서부이촌동입구</td>\n",
744:        "      <td>2703</td>\n",
745:        "      <td>8094</td>\n",
746:        "    </tr>\n",
747:        "    <tr>\n",
748:        "      <th>6</th>\n",
749:        "      <td>17</td>\n",
750:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
751:        "      <td>72995</td>\n",
752:        "      <td>이촌2동대림아파트.새남터성지</td>\n",
753:        "      <td>1602</td>\n",
754:        "      <td>7579</td>\n",
755:        "    </tr>\n",
756:        "    <tr>\n",
757:        "      <th>7</th>\n",
758:        "      <td>17</td>\n",
759:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
760:        "      <td>72996</td>\n",
761:        "      <td>이촌2동주민센터</td>\n",
762:        "      <td>1605</td>\n",
763:        "      <td>5088</td>\n",
764:        "    </tr>\n",
765:        "    <tr>\n",
766:        "      <th>8</th>\n",
767:        "      <td>17</td>\n",
768:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
769:        "      <td>72997</td>\n",
770:        "      <td>이촌로입구.성촌공원앞</td>\n",
771:        "      <td>389</td>\n",
772:        "      <td>1298</td>\n",
773:        "    </tr>\n",
774:        "  </tbody>\n",
775:        "</table>\n",
776:        "</div>"
777:       ],
778:       "text/plain": [
779:        "  노선번호                    노선명  버스정류장ID           버스정류장명  승차승객수  하차승객수\n",
780:        "0   17  0017번(용산차고지~신용산역3번출구)  8503228        용산차고지(가상)     25      5\n",
781:        "1   17  0017번(용산차고지~신용산역3번출구)  8503189          신용산지하차도    735     21\n",
782:        "2   17  0017번(용산차고지~신용산역3번출구)    72992              용산역  22519    352\n",
783:        "3   17  0017번(용산차고지~신용산역3번출구)    72314         용산푸르지오써밋   1782    488\n",
784:        "4   17  0017번(용산차고지~신용산역3번출구)    72993           한강대교북단   7261   1998\n",
785:        "5   17  0017번(용산차고지~신용산역3번출구)    72994          서부이촌동입구   2703   8094\n",
786:        "6   17  0017번(용산차고지~신용산역3번출구)    72995  이촌2동대림아파트.새남터성지   1602   7579\n",
787:        "7   17  0017번(용산차고지~신용산역3번출구)    72996         이촌2동주민센터   1605   5088\n",
788:        "8   17  0017번(용산차고지~신용산역3번출구)    72997      이촌로입구.성촌공원앞    389   1298"
789:       ]
790:      },
791:      "execution_count": 102,
792:      "metadata": {},
793:      "output_type": "execute_result"
794:     }
795:    ],
796:    "source": [
797:     "bus_station[['노선번호','노선명','버스정류장ID','버스정류장명','승차승객수','하차승객수']].head(9)   # 상위 9 라인만 출력"
798:    ]
799:   },
800:   {
801:    "cell_type": "markdown",
802:    "id": "fe2b1ccf-cd25-4cb0-8252-99aaea7644ba",
803:    "metadata": {},
804:    "source": [
805:     "### 이름(Label)으로 접근하느냐(loc), 위치를 나타내는 정수(Integer)로 접근하느냐(iloc)"
806:    ]
807:   },
808:   {
809:    "cell_type": "code",
810:    "execution_count": 103,
811:    "id": "97fe4db3-8757-4091-9c6d-6e605cfb8d75",
812:    "metadata": {},
813:    "outputs": [
814:     {
815:      "data": {
816:       "text/html": [
817:        "<div>\n",
818:        "<style scoped>\n",
819:        "    .dataframe tbody tr th:only-of-type {\n",
820:        "        vertical-align: middle;\n",
821:        "    }\n",
822:        "\n",
823:        "    .dataframe tbody tr th {\n",
824:        "        vertical-align: top;\n",
825:        "    }\n",
826:        "\n",
827:        "    .dataframe thead th {\n",
828:        "        text-align: right;\n",
829:        "    }\n",
830:        "</style>\n",
831:        "<table border=\"1\" class=\"dataframe\">\n",
832:        "  <thead>\n",
833:        "    <tr style=\"text-align: right;\">\n",
834:        "      <th></th>\n",
835:        "      <th>사용월</th>\n",
836:        "      <th>노선ID</th>\n",
837:        "      <th>노선번호</th>\n",
838:        "      <th>노선명</th>\n",
839:        "      <th>버스정류장ID</th>\n",
840:        "      <th>버스정류장명</th>\n",
841:        "      <th>승차승객수</th>\n",
842:        "      <th>하차승객수</th>\n",
843:        "    </tr>\n",
844:        "  </thead>\n",
845:        "  <tbody>\n",
846:        "    <tr>\n",
847:        "      <th>1</th>\n",
848:        "      <td>2026-05</td>\n",
849:        "      <td>11110897</td>\n",
850:        "      <td>17</td>\n",
851:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
852:        "      <td>8503189</td>\n",
853:        "      <td>신용산지하차도</td>\n",
854:        "      <td>735</td>\n",
855:        "      <td>21</td>\n",
856:        "    </tr>\n",
857:        "    <tr>\n",
858:        "      <th>2</th>\n",
859:        "      <td>2026-05</td>\n",
860:        "      <td>11110897</td>\n",
861:        "      <td>17</td>\n",
862:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
863:        "      <td>72992</td>\n",
864:        "      <td>용산역</td>\n",
865:        "      <td>22519</td>\n",
866:        "      <td>352</td>\n",
867:        "    </tr>\n",
868:        "    <tr>\n",
869:        "      <th>3</th>\n",
870:        "      <td>2026-05</td>\n",
871:        "      <td>11110897</td>\n",
872:        "      <td>17</td>\n",
873:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
874:        "      <td>72314</td>\n",
875:        "      <td>용산푸르지오써밋</td>\n",
876:        "      <td>1782</td>\n",
877:        "      <td>488</td>\n",
878:        "    </tr>\n",
879:        "    <tr>\n",
880:        "      <th>4</th>\n",
881:        "      <td>2026-05</td>\n",
882:        "      <td>11110897</td>\n",
883:        "      <td>17</td>\n",
884:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
885:        "      <td>72993</td>\n",
886:        "      <td>한강대교북단</td>\n",
887:        "      <td>7261</td>\n",
888:        "      <td>1998</td>\n",
889:        "    </tr>\n",
890:        "  </tbody>\n",
891:        "</table>\n",
892:        "</div>"
893:       ],
894:       "text/plain": [
895:        "       사용월      노선ID 노선번호                    노선명  버스정류장ID    버스정류장명  승차승객수  \\\n",
896:        "1  2026-05  11110897   17  0017번(용산차고지~신용산역3번출구)  8503189   신용산지하차도    735   \n",
897:        "2  2026-05  11110897   17  0017번(용산차고지~신용산역3번출구)    72992       용산역  22519   \n",
898:        "3  2026-05  11110897   17  0017번(용산차고지~신용산역3번출구)    72314  용산푸르지오써밋   1782   \n",
899:        "4  2026-05  11110897   17  0017번(용산차고지~신용산역3번출구)    72993    한강대교북단   7261   \n",
900:        "\n",
901:        "   하차승객수  \n",
902:        "1     21  \n",
903:        "2    352  \n",
904:        "3    488  \n",
905:        "4   1998  "
906:       ]
907:      },
908:      "execution_count": 103,
909:      "metadata": {},
910:      "output_type": "execute_result"
911:     }
912:    ],
913:    "source": [
914:     "bus_station.iloc[1:5]"
915:    ]
916:   },
917:   {
918:    "cell_type": "code",
919:    "execution_count": null,
920:    "id": "b67ae23c-0577-46cf-aa9a-4635ae7202fe",
921:    "metadata": {},
922:    "outputs": [],
923:    "source": []
924:   },
925:   {
926:    "cell_type": "markdown",
927:    "id": "9b4e0acd-50ce-42bc-96f6-2ba35a5d5aaf",
928:    "metadata": {},
929:    "source": [
930:     "### loc iloc practice"
931:    ]
932:   },
933:   {
934:    "cell_type": "code",
935:    "execution_count": 104,
936:    "id": "07090a55-f00a-472b-9656-faf0d215c447",
937:    "metadata": {},
938:    "outputs": [
939:     {
940:      "data": {
941:       "text/plain": [
942:        "사용월                      2026-05\n",
943:        "노선ID                    11110897\n",
944:        "노선번호                          17\n",
945:        "노선명        0017번(용산차고지~신용산역3번출구)\n",
946:        "버스정류장ID                  8503189\n",
947:        "버스정류장명                   신용산지하차도\n",
948:        "승차승객수                        735\n",
949:        "하차승객수                         21\n",
950:        "Name: 1, dtype: object"
951:       ]
952:      },
953:      "execution_count": 104,
954:      "metadata": {},
955:      "output_type": "execute_result"
956:     }
957:    ],
958:    "source": [
959:     "bus_station.iloc[1]"
960:    ]
961:   },
962:   {
963:    "cell_type": "code",
964:    "execution_count": 105,
965:    "id": "61d0ba73-e7f5-42c8-9f17-421d2b5cadd2",
966:    "metadata": {},
967:    "outputs": [
968:     {
969:      "data": {
970:       "text/html": [
971:        "<div>\n",
972:        "<style scoped>\n",
973:        "    .dataframe tbody tr th:only-of-type {\n",
974:        "        vertical-align: middle;\n",
975:        "    }\n",
976:        "\n",
977:        "    .dataframe tbody tr th {\n",
978:        "        vertical-align: top;\n",
979:        "    }\n",
980:        "\n",
981:        "    .dataframe thead th {\n",
982:        "        text-align: right;\n",
983:        "    }\n",
984:        "</style>\n",
985:        "<table border=\"1\" class=\"dataframe\">\n",
986:        "  <thead>\n",
987:        "    <tr style=\"text-align: right;\">\n",
988:        "      <th></th>\n",
989:        "      <th>사용월</th>\n",
990:        "      <th>노선ID</th>\n",
991:        "      <th>노선번호</th>\n",
992:        "      <th>노선명</th>\n",
993:        "      <th>버스정류장ID</th>\n",
994:        "      <th>버스정류장명</th>\n",
995:        "      <th>승차승객수</th>\n",
996:        "      <th>하차승객수</th>\n",
997:        "    </tr>\n",
998:        "  </thead>\n",
999:        "  <tbody>\n",
1000:        "    <tr>\n",
1001:        "      <th>1</th>\n",
1002:        "      <td>2026-05</td>\n",
1003:        "      <td>11110897</td>\n",
1004:        "      <td>17</td>\n",
1005:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
1006:        "      <td>8503189</td>\n",
1007:        "      <td>신용산지하차도</td>\n",
1008:        "      <td>735</td>\n",
1009:        "      <td>21</td>\n",
1010:        "    </tr>\n",
1011:        "    <tr>\n",
1012:        "      <th>2</th>\n",
1013:        "      <td>2026-05</td>\n",
1014:        "      <td>11110897</td>\n",
1015:        "      <td>17</td>\n",
1016:        "      <td>0017번(용산차고지~신용산역3번출구)</td>\n",
1017:        "      <td>72992</td>\n",
1018:        "      <td>용산역</td>\n",
1019:        "      <td>22519</td>\n",
1020:        "      <td>352</td>\n",
1021:        "    </tr>\n",
1022:        "  </tbody>\n",
1023:        "</table>\n",
1024:        "</div>"
1025:       ],
1026:       "text/plain": [
1027:        "       사용월      노선ID 노선번호                    노선명  버스정류장ID   버스정류장명  승차승객수  \\\n",
1028:        "1  2026-05  11110897   17  0017번(용산차고지~신용산역3번출구)  8503189  신용산지하차도    735   \n",
1029:        "2  2026-05  11110897   17  0017번(용산차고지~신용산역3번출구)    72992      용산역  22519   \n",
1030:        "\n",
1031:        "   하차승객수  \n",
1032:        "1     21  \n",
1033:        "2    352  "
1034:       ]
1035:      },
1036:      "execution_count": 105,
1037:      "metadata": {},
1038:      "output_type": "execute_result"
1039:     }
1040:    ],
1041:    "source": [
1042:     "bus_station.iloc[[1,2]]     # 복수는 두개의 대괄호"
1043:    ]
1044:   },
1045:   {
1046:    "cell_type": "code",
1047:    "execution_count": 106,
1048:    "id": "f5ae1943-d8ff-44cb-8355-8769d2dbe4d4",
1049:    "metadata": {},
1050:    "outputs": [
1051:     {
1052:      "data": {
1053:       "text/html": [
1054:        "<div>\n",
1055:        "<style scoped>\n",
1056:        "    .dataframe tbody tr th:only-of-type {\n",
1057:        "        vertical-align: middle;\n",
1058:        "    }\n",
1059:        "\n",
1060:        "    .dataframe tbody tr th {\n",
1061:        "        vertical-align: top;\n",
1062:        "    }\n",
1063:        "\n",
1064:        "    .dataframe thead th {\n",
1065:        "        text-align: right;\n",
1066:        "    }\n",
1067:        "</style>\n",
1068:        "<table border=\"1\" class=\"dataframe\">\n",
1069:        "  <thead>\n",
1070:        "    <tr style=\"text-align: right;\">\n",
1071:        "      <th></th>\n",
1072:        "      <th>버스정류장명</th>\n",
1073:        "      <th>승차승객수</th>\n",
1074:        "      <th>하차승객수</th>\n",
1075:        "    </tr>\n",
1076:        "  </thead>\n",
1077:        "  <tbody>\n",
1078:        "    <tr>\n",
1079:        "      <th>0</th>\n",
1080:        "      <td>용산차고지(가상)</td>\n",
1081:        "      <td>25</td>\n",
1082:        "      <td>5</td>\n",
1083:        "    </tr>\n",
1084:        "    <tr>\n",
1085:        "      <th>1</th>\n",
1086:        "      <td>신용산지하차도</td>\n",
1087:        "      <td>735</td>\n",
1088:        "      <td>21</td>\n",
1089:        "    </tr>\n",
1090:        "    <tr>\n",
1091:        "      <th>2</th>\n",
1092:        "      <td>용산역</td>\n",
1093:        "      <td>22519</td>\n",
1094:        "      <td>352</td>\n",
1095:        "    </tr>\n",
1096:        "    <tr>\n",
1097:        "      <th>3</th>\n",
1098:        "      <td>용산푸르지오써밋</td>\n",
1099:        "      <td>1782</td>\n",
1100:        "      <td>488</td>\n",
1101:        "    </tr>\n",
1102:        "  </tbody>\n",
1103:        "</table>\n",
1104:        "</div>"
1105:       ],
1106:       "text/plain": [
1107:        "      버스정류장명  승차승객수  하차승객수\n",
1108:        "0  용산차고지(가상)     25      5\n",
1109:        "1    신용산지하차도    735     21\n",
1110:        "2        용산역  22519    352\n",
1111:        "3   용산푸르지오써밋   1782    488"
1112:       ]
1113:      },
1114:      "execution_count": 106,
1115:      "metadata": {},
1116:      "output_type": "execute_result"
1117:     }
1118:    ],
1119:    "source": [
1120:     "bus_station.loc[0:3, '버스정류장명':'하차승객수']        # 버스정류장명  부터 하차승객수 사이의(포함) 모든 열을 선택하며, 0번부터 3번째 행까지 출력한다."
1121:    ]
1122:   },
1123:   {
1124:    "cell_type": "code",
1125:    "execution_count": 107,
1126:    "id": "a7fb562c-1388-4aef-92bc-3dbed7c66d1a",
1127:    "metadata": {},
1128:    "outputs": [
1129:     {
1130:      "data": {
1131:       "text/html": [
1132:        "<div>\n",
1133:        "<style scoped>\n",
1134:        "    .dataframe tbody tr th:only-of-type {\n",
1135:        "        vertical-align: middle;\n",
1136:        "    }\n",
1137:        "\n",
1138:        "    .dataframe tbody tr th {\n",
1139:        "        vertical-align: top;\n",
1140:        "    }\n",
1141:        "\n",
1142:        "    .dataframe thead th {\n",
1143:        "        text-align: right;\n",
1144:        "    }\n",
1145:        "</style>\n",
1146:        "<table border=\"1\" class=\"dataframe\">\n",
1147:        "  <thead>\n",
1148:        "    <tr style=\"text-align: right;\">\n",
1149:        "      <th></th>\n",
1150:        "      <th>버스정류장명</th>\n",
1151:        "      <th>승차승객수</th>\n",
1152:        "      <th>하차승객수</th>\n",
1153:        "    </tr>\n",
1154:        "  </thead>\n",
1155:        "  <tbody>\n",
1156:        "    <tr>\n",
1157:        "      <th>0</th>\n",
1158:        "      <td>용산차고지(가상)</td>\n",
1159:        "      <td>25</td>\n",
1160:        "      <td>5</td>\n",
1161:        "    </tr>\n",
1162:        "    <tr>\n",
1163:        "      <th>1</th>\n",
1164:        "      <td>신용산지하차도</td>\n",
1165:        "      <td>735</td>\n",
1166:        "      <td>21</td>\n",
1167:        "    </tr>\n",
1168:        "    <tr>\n",
1169:        "      <th>2</th>\n",
1170:        "      <td>용산역</td>\n",
1171:        "      <td>22519</td>\n",
1172:        "      <td>352</td>\n",
1173:        "    </tr>\n",
1174:        "    <tr>\n",
1175:        "      <th>3</th>\n",
1176:        "      <td>용산푸르지오써밋</td>\n",
1177:        "      <td>1782</td>\n",
1178:        "      <td>488</td>\n",
1179:        "    </tr>\n",
1180:        "    <tr>\n",
1181:        "      <th>4</th>\n",
1182:        "      <td>한강대교북단</td>\n",
1183:        "      <td>7261</td>\n",
1184:        "      <td>1998</td>\n",
1185:        "    </tr>\n",
1186:        "  </tbody>\n",
1187:        "</table>\n",
1188:        "</div>"
1189:       ],
1190:       "text/plain": [
1191:        "      버스정류장명  승차승객수  하차승객수\n",
1192:        "0  용산차고지(가상)     25      5\n",
1193:        "1    신용산지하차도    735     21\n",
1194:        "2        용산역  22519    352\n",
1195:        "3   용산푸르지오써밋   1782    488\n",
1196:        "4     한강대교북단   7261   1998"
1197:       ]
1198:      },
1199:      "execution_count": 107,
1200:      "metadata": {},
1201:      "output_type": "execute_result"
1202:     }
1203:    ],
1204:    "source": [
1205:     "bus_station.loc[0:4, '버스정류장명':'하차승객수']"
1206:    ]
1207:   },
1208:   {
1209:    "cell_type": "markdown",
1210:    "id": "cea82a90-4679-436f-ab77-8a1e8635ac9e",
1211:    "metadata": {},
1212:    "source": [
1213:     "### 소트 정렬하기"
1214:    ]
1215:   },
1216:   {
1217:    "cell_type": "code",
1218:    "execution_count": 108,
1219:    "id": "0e57e9e9-4a30-461c-b1f1-e8f9e7423cc2",
1220:    "metadata": {},
1221:    "outputs": [
1222:     {
1223:      "data": {
1224:       "text/html": [
1225:        "<div>\n",
1226:        "<style scoped>\n",
1227:        "    .dataframe tbody tr th:only-of-type {\n",
1228:        "        vertical-align: middle;\n",
1229:        "    }\n",
1230:        "\n",
1231:        "    .dataframe tbody tr th {\n",
1232:        "        vertical-align: top;\n",
1233:        "    }\n",
1234:        "\n",
1235:        "    .dataframe thead th {\n",
1236:        "        text-align: right;\n",
1237:        "    }\n",
1238:        "</style>\n",
1239:        "<table border=\"1\" class=\"dataframe\">\n",
1240:        "  <thead>\n",
1241:        "    <tr style=\"text-align: right;\">\n",
1242:        "      <th></th>\n",
1243:        "      <th>사용월</th>\n",
1244:        "      <th>노선ID</th>\n",
1245:        "      <th>노선번호</th>\n",
1246:        "      <th>노선명</th>\n",
1247:        "      <th>버스정류장ID</th>\n",
1248:        "      <th>버스정류장명</th>\n",
1249:        "      <th>승차승객수</th>\n",
1250:        "      <th>하차승객수</th>\n",
1251:        "    </tr>\n",
1252:        "  </thead>\n",
1253:        "  <tbody>\n",
1254:        "    <tr>\n",
1255:        "      <th>37425</th>\n",
1256:        "      <td>2026-05</td>\n",
1257:        "      <td>11110590</td>\n",
1258:        "      <td>동대문01</td>\n",
1259:        "      <td>동대문01(회기역~경희의료원)</td>\n",
1260:        "      <td>9008470</td>\n",
1261:        "      <td>회기역</td>\n",
1262:        "      <td>128886</td>\n",
1263:        "      <td>62014</td>\n",
1264:        "    </tr>\n",
1265:        "    <tr>\n",
1266:        "      <th>40809</th>\n",
1267:        "      <td>2026-05</td>\n",
1268:        "      <td>11110696</td>\n",
1269:        "      <td>양천01</td>\n",
1270:        "      <td>양천01(등촌역~당산역)</td>\n",
1271:        "      <td>9008732</td>\n",
1272:        "      <td>당산역.지하철2호선</td>\n",
1273:        "      <td>95796</td>\n",
1274:        "      <td>75634</td>\n",
1275:        "    </tr>\n",
1276:        "    <tr>\n",
1277:        "      <th>38710</th>\n",
1278:        "      <td>2026-05</td>\n",
1279:        "      <td>11110641</td>\n",
1280:        "      <td>서대문03</td>\n",
1281:        "      <td>서대문03(홍은2동주민센터~신촌역)</td>\n",
1282:        "      <td>9013927</td>\n",
1283:        "      <td>신촌전철역</td>\n",
1284:        "      <td>91035</td>\n",
1285:        "      <td>30804</td>\n",
1286:        "    </tr>\n",
1287:        "    <tr>\n",
1288:        "      <th>37428</th>\n",
1289:        "      <td>2026-05</td>\n",
1290:        "      <td>11110590</td>\n",
1291:        "      <td>동대문01</td>\n",
1292:        "      <td>동대문01(회기역~경희의료원)</td>\n",
1293:        "      <td>9011737</td>\n",
1294:        "      <td>경희대의료원</td>\n",
1295:        "      <td>84937</td>\n",
1296:        "      <td>82737</td>\n",
1297:        "    </tr>\n",
1298:        "    <tr>\n",
1299:        "      <th>49</th>\n",
1300:        "      <td>2026-05</td>\n",
1301:        "      <td>11110475</td>\n",
1302:        "      <td>01A</td>\n",
1303:        "      <td>01A번(예장주차장~예장주차장)</td>\n",
1304:        "      <td>77296</td>\n",
1305:        "      <td>남산서울타워</td>\n",
1306:        "      <td>81252</td>\n",
1307:        "      <td>62410</td>\n",
1308:        "    </tr>\n",
1309:        "    <tr>\n",
1310:        "      <th>...</th>\n",
1311:        "      <td>...</td>\n",
1312:        "      <td>...</td>\n",
1313:        "      <td>...</td>\n",
1314:        "      <td>...</td>\n",
1315:        "      <td>...</td>\n",
1316:        "      <td>...</td>\n",
1317:        "      <td>...</td>\n",
1318:        "      <td>...</td>\n",
1319:        "    </tr>\n",
1320:        "    <tr>\n",
1321:        "      <th>31655</th>\n",
1322:        "      <td>2026-05</td>\n",
1323:        "      <td>41110152</td>\n",
1324:        "      <td>N37</td>\n",
1325:        "      <td>N37번(송파공영차고지~진관공영차고지)</td>\n",
1326:        "      <td>9010867</td>\n",
1327:        "      <td>복정역환승주차장</td>\n",
1328:        "      <td>0</td>\n",
1329:        "      <td>282</td>\n",
1330:        "    </tr>\n",
1331:        "    <tr>\n",
1332:        "      <th>6428</th>\n",
1333:        "      <td>2026-05</td>\n",
1334:        "      <td>11110358</td>\n",
1335:        "      <td>2016</td>\n",
1336:        "      <td>2016번(중랑차고지~이촌2동)</td>\n",
1337:        "      <td>7000038</td>\n",
1338:        "      <td>중랑공영차고지(가상)</td>\n",
1339:        "      <td>0</td>\n",
1340:        "      <td>17</td>\n",
1341:        "    </tr>\n",
1342:        "    <tr>\n",
1343:        "      <th>6288</th>\n",
1344:        "      <td>2026-05</td>\n",
1345:        "      <td>11110175</td>\n",
1346:        "      <td>2015</td>\n",
1347:        "      <td>2015번(신내공영차고지~동대문운동장)</td>\n",
1348:        "      <td>32570</td>\n",
1349:        "      <td>중랑공영차고지(가상)</td>\n",
1350:        "      <td>0</td>\n",
1351:        "      <td>20</td>\n",
1352:        "    </tr>\n",
1353:        "    <tr>\n",
1354:        "      <th>39221</th>\n",
1355:        "      <td>2026-05</td>\n",
1356:        "      <td>11410025</td>\n",
1357:        "      <td>서울09퇴근</td>\n",
1358:        "      <td>서울09퇴근(노원역~의정부시고산지구)</td>\n",
1359:        "      <td>8503180</td>\n",
1360:        "      <td>민락교</td>\n",
1361:        "      <td>0</td>\n",
1362:        "      <td>44</td>\n",
1363:        "    </tr>\n",
1364:        "    <tr>\n",
1365:        "      <th>39220</th>\n",
1366:        "      <td>2026-05</td>\n",
1367:        "      <td>11410025</td>\n",
1368:        "      <td>서울09퇴근</td>\n",
1369:        "      <td>서울09퇴근(노원역~의정부시고산지구)</td>\n",
1370:        "      <td>8503179</td>\n",
1371:        "      <td>정음마을고산2단지.고산종합사회복지관</td>\n",
1372:        "      <td>0</td>\n",
1373:        "      <td>56</td>\n",
1374:        "    </tr>\n",
1375:        "  </tbody>\n",
1376:        "</table>\n",
1377:        "<p>42000 rows × 8 columns</p>\n",
1378:        "</div>"
1379:       ],
1380:       "text/plain": [
1381:        "           사용월      노선ID    노선번호                    노선명  버스정류장ID  \\\n",
1382:        "37425  2026-05  11110590   동대문01       동대문01(회기역~경희의료원)  9008470   \n",
1383:        "40809  2026-05  11110696    양천01          양천01(등촌역~당산역)  9008732   \n",
1384:        "38710  2026-05  11110641   서대문03    서대문03(홍은2동주민센터~신촌역)  9013927   \n",
1385:        "37428  2026-05  11110590   동대문01       동대문01(회기역~경희의료원)  9011737   \n",
1386:        "49     2026-05  11110475     01A      01A번(예장주차장~예장주차장)    77296   \n",
1387:        "...        ...       ...     ...                    ...      ...   \n",
1388:        "31655  2026-05  41110152     N37  N37번(송파공영차고지~진관공영차고지)  9010867   \n",
1389:        "6428   2026-05  11110358    2016      2016번(중랑차고지~이촌2동)  7000038   \n",
1390:        "6288   2026-05  11110175    2015  2015번(신내공영차고지~동대문운동장)    32570   \n",
1391:        "39221  2026-05  11410025  서울09퇴근   서울09퇴근(노원역~의정부시고산지구)  8503180   \n",
1392:        "39220  2026-05  11410025  서울09퇴근   서울09퇴근(노원역~의정부시고산지구)  8503179   \n",
1393:        "\n",
1394:        "                    버스정류장명   승차승객수  하차승객수  \n",
1395:        "37425                  회기역  128886  62014  \n",
1396:        "40809           당산역.지하철2호선   95796  75634  \n",
1397:        "38710                신촌전철역   91035  30804  \n",
1398:        "37428               경희대의료원   84937  82737  \n",
1399:        "49                  남산서울타워   81252  62410  \n",
1400:        "...                    ...     ...    ...  \n",
1401:        "31655             복정역환승주차장       0    282  \n",
1402:        "6428           중랑공영차고지(가상)       0     17  \n",
1403:        "6288           중랑공영차고지(가상)       0     20  \n",
1404:        "39221                  민락교       0     44  \n",
1405:        "39220  정음마을고산2단지.고산종합사회복지관       0     56  \n",
1406:        "\n",
1407:        "[42000 rows x 8 columns]"
1408:       ]
1409:      },
1410:      "execution_count": 108,
1411:      "metadata": {},
1412:      "output_type": "execute_result"
1413:     }
1414:    ],
1415:    "source": [
1416:     "bus_station.sort_values(by='승차승객수', ascending=False)        # 승차승객수가 제일 큰 대로 내림차순 카운트다운"
1417:    ]
1418:   },
1419:   {
1420:    "cell_type": "code",
1421:    "execution_count": 109,
1422:    "id": "b20e648f",
1423:    "metadata": {},
1424:    "outputs": [
1425:     {
1426:      "data": {
1427:       "text/html": [
1428:        "<div>\n",
1429:        "<style scoped>\n",
1430:        "    .dataframe tbody tr th:only-of-type {\n",
1431:        "        vertical-align: middle;\n",
1432:        "    }\n",
1433:        "\n",
1434:        "    .dataframe tbody tr th {\n",
1435:        "        vertical-align: top;\n",
1436:        "    }\n",
1437:        "\n",
1438:        "    .dataframe thead th {\n",
1439:        "        text-align: right;\n",
1440:        "    }\n",
1441:        "</style>\n",
1442:        "<table border=\"1\" class=\"dataframe\">\n",
1443:        "  <thead>\n",
1444:        "    <tr style=\"text-align: right;\">\n",
1445:        "      <th></th>\n",
1446:        "      <th>사용월</th>\n",
1447:        "      <th>노선ID</th>\n",
1448:        "      <th>노선번호</th>\n",
1449:        "      <th>노선명</th>\n",
1450:        "      <th>버스정류장ID</th>\n",
1451:        "      <th>버스정류장명</th>\n",
1452:        "      <th>승차승객수</th>\n",
1453:        "      <th>하차승객수</th>\n",
1454:        "    </tr>\n",
1455:        "  </thead>\n",
1456:        "  <tbody>\n",
1457:        "    <tr>\n",
1458:        "      <th>30548</th>\n",
1459:        "      <td>2026-05</td>\n",
1460:        "      <td>11110378</td>\n",
1461:        "      <td>N15</td>\n",
1462:        "      <td>N15번(우이동성원아파트~남태령역)</td>\n",
1463:        "      <td>8502312</td>\n",
1464:        "      <td>사당자동차학원</td>\n",
1465:        "      <td>0</td>\n",
1466:        "      <td>40</td>\n",
1467:        "    </tr>\n",
1468:        "    <tr>\n",
1469:        "      <th>21321</th>\n",
1470:        "      <td>2026-05</td>\n",
1471:        "      <td>11110835</td>\n",
1472:        "      <td>6611</td>\n",
1473:        "      <td>6611번(개화역광역환승센터~한강버스마곡선착장)</td>\n",
1474:        "      <td>8502032</td>\n",

(Output capped at 50 KB. Showing lines 1-1474. Use offset=1475 to continue.)
</content>
```

---

## Assistant (Build · DeepSeek V4 Flash Free · 4.2s)

_Thinking:_

Let me also check the remaining part of the 20260719-일요실습1.ipynb to see the full context, and also look at the 실습 폴더 and the original datasets folder.

Now let me check the practice folders for more context:

**Tool: read**

**Input:**
```json
{
  "filePath": "C:\\Users\\Administrator\\Documents\\GitHub\\kw-competition-practice\\20260704-토요실습1"
}
```

**Output:**
```
<path>C:\Users\Administrator\Documents\GitHub\kw-competition-practice\20260704-토요실습1</path>
<type>directory</type>
<entries>
20260704-토요실습1.md
output_25_1.png
output_62_1.png
output_63_1.png
output_64_1.png
output_70_0.png
output_89_1.png
output_90_0.png

(8 entries)
</entries>
```

**Tool: read**

**Input:**
```json
{
  "filePath": "C:\\Users\\Administrator\\Documents\\GitHub\\kw-competition-practice\\20260705-일요실습1"
}
```

**Output:**
```
<path>C:\Users\Administrator\Documents\GitHub\kw-competition-practice\20260705-일요실습1</path>
<type>directory</type>
<entries>
20260705-일요실습1.md
output_15_0.png
output_18_0.png
output_22_0.png
output_46_1.png
output_50_0.png
output_51_0.png
output_72_0.png
output_73_0.png
output_74_0.png
output_75_0.png
output_8_0.png
output_9_0.png
output_9_1.png

(14 entries)
</entries>
```

**Tool: read**

**Input:**
```json
{
  "filePath": "C:\\Users\\Administrator\\Documents\\GitHub\\kw-competition-practice\\20260719-일요실습1.ipynb",
  "offset": 1418
}
```

**Output:**
```
<path>C:\Users\Administrator\Documents\GitHub\kw-competition-practice\20260719-일요실습1.ipynb</path>
<type>file</type>
<content>
1418:   },
1419:   {
1420:    "cell_type": "code",
1421:    "execution_count": 109,
1422:    "id": "b20e648f",
1423:    "metadata": {},
1424:    "outputs": [
1425:     {
1426:      "data": {
1427:       "text/html": [
1428:        "<div>\n",
1429:        "<style scoped>\n",
1430:        "    .dataframe tbody tr th:only-of-type {\n",
1431:        "        vertical-align: middle;\n",
1432:        "    }\n",
1433:        "\n",
1434:        "    .dataframe tbody tr th {\n",
1435:        "        vertical-align: top;\n",
1436:        "    }\n",
1437:        "\n",
1438:        "    .dataframe thead th {\n",
1439:        "        text-align: right;\n",
1440:        "    }\n",
1441:        "</style>\n",
1442:        "<table border=\"1\" class=\"dataframe\">\n",
1443:        "  <thead>\n",
1444:        "    <tr style=\"text-align: right;\">\n",
1445:        "      <th></th>\n",
1446:        "      <th>사용월</th>\n",
1447:        "      <th>노선ID</th>\n",
1448:        "      <th>노선번호</th>\n",
1449:        "      <th>노선명</th>\n",
1450:        "      <th>버스정류장ID</th>\n",
1451:        "      <th>버스정류장명</th>\n",
1452:        "      <th>승차승객수</th>\n",
1453:        "      <th>하차승객수</th>\n",
1454:        "    </tr>\n",
1455:        "  </thead>\n",
1456:        "  <tbody>\n",
1457:        "    <tr>\n",
1458:        "      <th>30548</th>\n",
1459:        "      <td>2026-05</td>\n",
1460:        "      <td>11110378</td>\n",
1461:        "      <td>N15</td>\n",
1462:        "      <td>N15번(우이동성원아파트~남태령역)</td>\n",
1463:        "      <td>8502312</td>\n",
1464:        "      <td>사당자동차학원</td>\n",
1465:        "      <td>0</td>\n",
1466:        "      <td>40</td>\n",
1467:        "    </tr>\n",
1468:        "    <tr>\n",
1469:        "      <th>21321</th>\n",
1470:        "      <td>2026-05</td>\n",
1471:        "      <td>11110835</td>\n",
1472:        "      <td>6611</td>\n",
1473:        "      <td>6611번(개화역광역환승센터~한강버스마곡선착장)</td>\n",
1474:        "      <td>8502032</td>\n",
1475:        "      <td>강서공영차고지(종점가상)</td>\n",
1476:        "      <td>0</td>\n",
1477:        "      <td>2</td>\n",
1478:        "    </tr>\n",
1479:        "    <tr>\n",
1480:        "      <th>24864</th>\n",
1481:        "      <td>2026-05</td>\n",
1482:        "      <td>41110011</td>\n",
1483:        "      <td>702A</td>\n",
1484:        "      <td>702A번(원당~종로1가)</td>\n",
1485:        "      <td>8502693</td>\n",
1486:        "      <td>숭례문(가상)</td>\n",
1487:        "      <td>0</td>\n",
1488:        "      <td>623</td>\n",
1489:        "    </tr>\n",
1490:        "    <tr>\n",
1491:        "      <th>29123</th>\n",
1492:        "      <td>2026-05</td>\n",
1493:        "      <td>91000042</td>\n",
1494:        "      <td>8773구산출</td>\n",
1495:        "      <td>8773구산출근(구산동~홍대입구역)</td>\n",
1496:        "      <td>8502690</td>\n",
1497:        "      <td>홍대입구역(가상)</td>\n",
1498:        "      <td>0</td>\n",
1499:        "      <td>118</td>\n",
1500:        "    </tr>\n",
1501:        "    <tr>\n",
1502:        "      <th>29269</th>\n",
1503:        "      <td>2026-05</td>\n",
1504:        "      <td>91000043</td>\n",
1505:        "      <td>8773홍대출</td>\n",
1506:        "      <td>8773홍대출근(홍대입구역~구산동)</td>\n",
1507:        "      <td>9339</td>\n",
1508:        "      <td>구산동주민센터</td>\n",
1509:        "      <td>0</td>\n",
1510:        "      <td>5</td>\n",
1511:        "    </tr>\n",
1512:        "    <tr>\n",
1513:        "      <th>...</th>\n",
1514:        "      <td>...</td>\n",
1515:        "      <td>...</td>\n",
1516:        "      <td>...</td>\n",
1517:        "      <td>...</td>\n",
1518:        "      <td>...</td>\n",
1519:        "      <td>...</td>\n",
1520:        "      <td>...</td>\n",
1521:        "      <td>...</td>\n",
1522:        "    </tr>\n",
1523:        "    <tr>\n",
1524:        "      <th>49</th>\n",
1525:        "      <td>2026-05</td>\n",
1526:        "      <td>11110475</td>\n",
1527:        "      <td>01A</td>\n",
1528:        "      <td>01A번(예장주차장~예장주차장)</td>\n",
1529:        "      <td>77296</td>\n",
1530:        "      <td>남산서울타워</td>\n",
1531:        "      <td>81252</td>\n",
1532:        "      <td>62410</td>\n",
1533:        "    </tr>\n",
1534:        "    <tr>\n",
1535:        "      <th>37428</th>\n",
1536:        "      <td>2026-05</td>\n",
1537:        "      <td>11110590</td>\n",
1538:        "      <td>동대문01</td>\n",
1539:        "      <td>동대문01(회기역~경희의료원)</td>\n",
1540:        "      <td>9011737</td>\n",
1541:        "      <td>경희대의료원</td>\n",
1542:        "      <td>84937</td>\n",
1543:        "      <td>82737</td>\n",
1544:        "    </tr>\n",
1545:        "    <tr>\n",
1546:        "      <th>38710</th>\n",
1547:        "      <td>2026-05</td>\n",
1548:        "      <td>11110641</td>\n",
1549:        "      <td>서대문03</td>\n",
1550:        "      <td>서대문03(홍은2동주민센터~신촌역)</td>\n",
1551:        "      <td>9013927</td>\n",
1552:        "      <td>신촌전철역</td>\n",
1553:        "      <td>91035</td>\n",
1554:        "      <td>30804</td>\n",
1555:        "    </tr>\n",
1556:        "    <tr>\n",
1557:        "      <th>40809</th>\n",
1558:        "      <td>2026-05</td>\n",
1559:        "      <td>11110696</td>\n",
1560:        "      <td>양천01</td>\n",
1561:        "      <td>양천01(등촌역~당산역)</td>\n",
1562:        "      <td>9008732</td>\n",
1563:        "      <td>당산역.지하철2호선</td>\n",
1564:        "      <td>95796</td>\n",
1565:        "      <td>75634</td>\n",
1566:        "    </tr>\n",
1567:        "    <tr>\n",
1568:        "      <th>37425</th>\n",
1569:        "      <td>2026-05</td>\n",
1570:        "      <td>11110590</td>\n",
1571:        "      <td>동대문01</td>\n",
1572:        "      <td>동대문01(회기역~경희의료원)</td>\n",
1573:        "      <td>9008470</td>\n",
1574:        "      <td>회기역</td>\n",
1575:        "      <td>128886</td>\n",
1576:        "      <td>62014</td>\n",
1577:        "    </tr>\n",
1578:        "  </tbody>\n",
1579:        "</table>\n",
1580:        "<p>42000 rows × 8 columns</p>\n",
1581:        "</div>"
1582:       ],
1583:       "text/plain": [
1584:        "           사용월      노선ID     노선번호                         노선명  버스정류장ID  \\\n",
1585:        "30548  2026-05  11110378      N15         N15번(우이동성원아파트~남태령역)  8502312   \n",
1586:        "21321  2026-05  11110835     6611  6611번(개화역광역환승센터~한강버스마곡선착장)  8502032   \n",
1587:        "24864  2026-05  41110011     702A              702A번(원당~종로1가)  8502693   \n",
1588:        "29123  2026-05  91000042  8773구산출         8773구산출근(구산동~홍대입구역)  8502690   \n",
1589:        "29269  2026-05  91000043  8773홍대출         8773홍대출근(홍대입구역~구산동)     9339   \n",
1590:        "...        ...       ...      ...                         ...      ...   \n",
1591:        "49     2026-05  11110475      01A           01A번(예장주차장~예장주차장)    77296   \n",
1592:        "37428  2026-05  11110590    동대문01            동대문01(회기역~경희의료원)  9011737   \n",
1593:        "38710  2026-05  11110641    서대문03         서대문03(홍은2동주민센터~신촌역)  9013927   \n",
1594:        "40809  2026-05  11110696     양천01               양천01(등촌역~당산역)  9008732   \n",
1595:        "37425  2026-05  11110590    동대문01            동대문01(회기역~경희의료원)  9008470   \n",
1596:        "\n",
1597:        "              버스정류장명   승차승객수  하차승객수  \n",
1598:        "30548        사당자동차학원       0     40  \n",
1599:        "21321  강서공영차고지(종점가상)       0      2  \n",
1600:        "24864        숭례문(가상)       0    623  \n",
1601:        "29123      홍대입구역(가상)       0    118  \n",
1602:        "29269        구산동주민센터       0      5  \n",
1603:        "...              ...     ...    ...  \n",
1604:        "49            남산서울타워   81252  62410  \n",
1605:        "37428         경희대의료원   84937  82737  \n",
1606:        "38710          신촌전철역   91035  30804  \n",
1607:        "40809     당산역.지하철2호선   95796  75634  \n",
1608:        "37425            회기역  128886  62014  \n",
1609:        "\n",
1610:        "[42000 rows x 8 columns]"
1611:       ]
1612:      },
1613:      "execution_count": 109,
1614:      "metadata": {},
1615:      "output_type": "execute_result"
1616:     }
1617:    ],
1618:    "source": [
1619:     "bus_station.sort_values(by='승차승객수', ascending=True)        # 승차승객수가 제일 작은대로 오름차순 카운트다운"
1620:    ]
1621:   },
1622:   {
1623:    "cell_type": "markdown",
1624:    "id": "4bdd8a1c-fde2-47ad-8c07-1b09c8028b87",
1625:    "metadata": {},
1626:    "source": [
1627:     "### 인덱스는 데이터를 찾는 기준이다"
1628:    ]
1629:   },
1630:   {
1631:    "cell_type": "code",
1632:    "execution_count": 110,
1633:    "id": "30b922cc-4b27-42ff-b8e9-c10d58e54e98",
1634:    "metadata": {},
1635:    "outputs": [
1636:     {
1637:      "data": {
1638:       "text/html": [
1639:        "<div>\n",
1640:        "<style scoped>\n",
1641:        "    .dataframe tbody tr th:only-of-type {\n",
1642:        "        vertical-align: middle;\n",
1643:        "    }\n",
1644:        "\n",
1645:        "    .dataframe tbody tr th {\n",
1646:        "        vertical-align: top;\n",
1647:        "    }\n",
1648:        "\n",
1649:        "    .dataframe thead th {\n",
1650:        "        text-align: right;\n",
1651:        "    }\n",
1652:        "</style>\n",
1653:        "<table border=\"1\" class=\"dataframe\">\n",
1654:        "  <thead>\n",
1655:        "    <tr style=\"text-align: right;\">\n",
1656:        "      <th></th>\n",
1657:        "      <th>버스정류장명</th>\n",
1658:        "      <th>승차승객수</th>\n",
1659:        "      <th>하차승객수</th>\n",
1660:        "    </tr>\n",
1661:        "    <tr>\n",
1662:        "      <th>버스정류장명</th>\n",
1663:        "      <th></th>\n",
1664:        "      <th></th>\n",
1665:        "      <th></th>\n",
1666:        "    </tr>\n",
1667:        "  </thead>\n",
1668:        "  <tbody>\n",
1669:        "    <tr>\n",
1670:        "      <th>용산차고지(가상)</th>\n",
1671:        "      <td>용산차고지(가상)</td>\n",
1672:        "      <td>25</td>\n",
1673:        "      <td>5</td>\n",
1674:        "    </tr>\n",
1675:        "    <tr>\n",
1676:        "      <th>신용산지하차도</th>\n",
1677:        "      <td>신용산지하차도</td>\n",
1678:        "      <td>735</td>\n",
1679:        "      <td>21</td>\n",
1680:        "    </tr>\n",
1681:        "    <tr>\n",
1682:        "      <th>용산역</th>\n",
1683:        "      <td>용산역</td>\n",
1684:        "      <td>22519</td>\n",
1685:        "      <td>352</td>\n",
1686:        "    </tr>\n",
1687:        "    <tr>\n",
1688:        "      <th>용산푸르지오써밋</th>\n",
1689:        "      <td>용산푸르지오써밋</td>\n",
1690:        "      <td>1782</td>\n",
1691:        "      <td>488</td>\n",
1692:        "    </tr>\n",
1693:        "    <tr>\n",
1694:        "      <th>한강대교북단</th>\n",
1695:        "      <td>한강대교북단</td>\n",
1696:        "      <td>7261</td>\n",
1697:        "      <td>1998</td>\n",
1698:        "    </tr>\n",
1699:        "    <tr>\n",
1700:        "      <th>...</th>\n",
1701:        "      <td>...</td>\n",
1702:        "      <td>...</td>\n",
1703:        "      <td>...</td>\n",
1704:        "    </tr>\n",
1705:        "    <tr>\n",
1706:        "      <th>압구정</th>\n",
1707:        "      <td>압구정</td>\n",
1708:        "      <td>4899</td>\n",
1709:        "      <td>3375</td>\n",
1710:        "    </tr>\n",
1711:        "    <tr>\n",
1712:        "      <th>옥수</th>\n",
1713:        "      <td>옥수</td>\n",
1714:        "      <td>5891</td>\n",
1715:        "      <td>3566</td>\n",
1716:        "    </tr>\n",
1717:        "    <tr>\n",
1718:        "      <th>성수</th>\n",
1719:        "      <td>성수</td>\n",
1720:        "      <td>4</td>\n",
1721:        "      <td>4</td>\n",
1722:        "    </tr>\n",
1723:        "    <tr>\n",
1724:        "      <th>뚝섬</th>\n",
1725:        "      <td>뚝섬</td>\n",
1726:        "      <td>8736</td>\n",
1727:        "      <td>6459</td>\n",
1728:        "    </tr>\n",
1729:        "    <tr>\n",
1730:        "      <th>잠실</th>\n",
1731:        "      <td>잠실</td>\n",
1732:        "      <td>9667</td>\n",
1733:        "      <td>12434</td>\n",
1734:        "    </tr>\n",
1735:        "  </tbody>\n",
1736:        "</table>\n",
1737:        "<p>42000 rows × 3 columns</p>\n",
1738:        "</div>"
1739:       ],
1740:       "text/plain": [
1741:        "              버스정류장명  승차승객수  하차승객수\n",
1742:        "버스정류장명                            \n",
1743:        "용산차고지(가상)  용산차고지(가상)     25      5\n",
1744:        "신용산지하차도      신용산지하차도    735     21\n",
1745:        "용산역              용산역  22519    352\n",
1746:        "용산푸르지오써밋    용산푸르지오써밋   1782    488\n",
1747:        "한강대교북단        한강대교북단   7261   1998\n",
1748:        "...              ...    ...    ...\n",
1749:        "압구정              압구정   4899   3375\n",
1750:        "옥수                옥수   5891   3566\n",
1751:        "성수                성수      4      4\n",
1752:        "뚝섬                뚝섬   8736   6459\n",
1753:        "잠실                잠실   9667  12434\n",
1754:        "\n",
1755:        "[42000 rows x 3 columns]"
1756:       ]
1757:      },
1758:      "execution_count": 110,
1759:      "metadata": {},
1760:      "output_type": "execute_result"
1761:     }
1762:    ],
1763:    "source": [
1764:     "boarding=bus_station[['버스정류장명','승차승객수','하차승객수']]         # 버스정류장명 승차승객수 하차승객수만 출력하고 boaring 이란 변수에 저장하고 그 변수를 출력\n",
1765:     "boarding.index=boarding['버스정류장명']                                  # 그리고 그 변수의 인덱스는 버스정류장명으로 한다.\n",
1766:     "boarding                                                                 # 그리고 그 변수를 출력"
1767:    ]
1768:   },
1769:   {
1770:    "cell_type": "code",
1771:    "execution_count": 111,
1772:    "id": "ff45ac8b-8724-4c61-99a0-738b7596e49c",
1773:    "metadata": {},
1774:    "outputs": [
1775:     {
1776:      "data": {
1777:       "text/html": [
1778:        "<div>\n",
1779:        "<style scoped>\n",
1780:        "    .dataframe tbody tr th:only-of-type {\n",
1781:        "        vertical-align: middle;\n",
1782:        "    }\n",
1783:        "\n",
1784:        "    .dataframe tbody tr th {\n",
1785:        "        vertical-align: top;\n",
1786:        "    }\n",
1787:        "\n",
1788:        "    .dataframe thead th {\n",
1789:        "        text-align: right;\n",
1790:        "    }\n",
1791:        "</style>\n",
1792:        "<table border=\"1\" class=\"dataframe\">\n",
1793:        "  <thead>\n",
1794:        "    <tr style=\"text-align: right;\">\n",
1795:        "      <th></th>\n",
1796:        "      <th>버스정류장명</th>\n",
1797:        "      <th>승차승객수</th>\n",
1798:        "      <th>하차승객수</th>\n",
1799:        "    </tr>\n",
1800:        "    <tr>\n",
1801:        "      <th>버스정류장명</th>\n",
1802:        "      <th></th>\n",
1803:        "      <th></th>\n",
1804:        "      <th></th>\n",
1805:        "    </tr>\n",
1806:        "  </thead>\n",
1807:        "  <tbody>\n",
1808:        "    <tr>\n",
1809:        "      <th>용산역</th>\n",
1810:        "      <td>용산역</td>\n",
1811:        "      <td>22519</td>\n",
1812:        "      <td>352</td>\n",
1813:        "    </tr>\n",
1814:        "    <tr>\n",
1815:        "      <th>용산역</th>\n",
1816:        "      <td>용산역</td>\n",
1817:        "      <td>3614</td>\n",
1818:        "      <td>73</td>\n",
1819:        "    </tr>\n",
1820:        "    <tr>\n",
1821:        "      <th>용산역</th>\n",
1822:        "      <td>용산역</td>\n",
1823:        "      <td>26481</td>\n",
1824:        "      <td>11246</td>\n",
1825:        "    </tr>\n",
1826:        "    <tr>\n",
1827:        "      <th>용산역</th>\n",
1828:        "      <td>용산역</td>\n",
1829:        "      <td>18543</td>\n",
1830:        "      <td>6505</td>\n",
1831:        "    </tr>\n",
1832:        "  </tbody>\n",
1833:        "</table>\n",
1834:        "</div>"
1835:       ],
1836:       "text/plain": [
1837:        "       버스정류장명  승차승객수  하차승객수\n",
1838:        "버스정류장명                     \n",
1839:        "용산역       용산역  22519    352\n",
1840:        "용산역       용산역   3614     73\n",
1841:        "용산역       용산역  26481  11246\n",
1842:        "용산역       용산역  18543   6505"
1843:       ]
1844:      },
1845:      "execution_count": 111,
1846:      "metadata": {},
1847:      "output_type": "execute_result"
1848:     }
1849:    ],
1850:    "source": [
1851:     "boarding.loc['용산역']   # boarding 변수에서 용산역에 대하여 값 모두 출력"
1852:    ]
1853:   },
1854:   {
1855:    "cell_type": "markdown",
1856:    "id": "a000ced3-2228-4153-96a9-c907419879ed",
1857:    "metadata": {},
1858:    "source": [
1859:     "### 그래프 시각화(boarding 함수)"
1860:    ]
1861:   },
1862:   {
1863:    "cell_type": "code",
1864:    "execution_count": 121,
1865:    "id": "6dc87f67-2464-4cba-b929-e8f845b21379",
1866:    "metadata": {},
1867:    "outputs": [
1868:     {
1869:      "data": {
1870:       "text/plain": [
1871:        "<function matplotlib.pyplot.show(close=None, block=None)>"
1872:       ]
1873:      },
1874:      "execution_count": 121,
1875:      "metadata": {},
1876:      "output_type": "execute_result"
1877:     },
1878:     {
1879:      "data": {
1880:       "image/png": "iVBORw0KGgoAAAANSUhEUgAAAkYAAAIfCAYAAACVXBNTAAAAOnRFWHRTb2Z0d2FyZQBNYXRwbG90bGliIHZlcnNpb24zLjEwLjAsIGh0dHBzOi8vbWF0cGxvdGxpYi5vcmcvlHJYcgAAAAlwSFlzAAAPYQAAD2EBqD+naQAAiblJREFUeJzs3XVYVFkDBvB3SMUAERHEwM61sLuxsFsM7DUWXF1z7QBb7MBc/WxFRdYEu7sVA0QRBUFAQWLmfH8wc5eRVmAA39/zzMNw89w7M3feOffcc2VCCAEiIiIigpamC0BERESUWTAYERERESkxGBEREREpMRgRERERKTEYERERESkxGBEREREpMRgRERERKTEYERERESkxGGUTMTExkMlkkMlkmDRpUqLTubi4SNM9ffo0yWXeu3cP48ePR7169WBmZoYcOXJAW1sbefLkQenSpdG5c2esX78eX758SVVZVet3cHD4qW1JjIODA5o0aZLg8jdt2oQmTZqgSZMmiIqKkoZv3bpVWqe3t3eK1xW3rIltT0JWrVolzZfcI255Bg4cCJlMBktLy0SXffr06RQvW/VwdXVNcFndunVL0fxxy2NiYgKZTIaBAwemeH+khLe3t7Q+FxeXH17Oly9fkn1/NWnSBDKZDDVq1EjRMpcvX57s+8fS0hIymQzt27f/0aIn6Ef3y44dO5J8TcuWLQsg/ntO9b+ZmVmqyhn32PPixYtUzZuUvn37okmTJnBycoo3rlevXmjSpAlmzJihNlxVjpkzZya63M+fPyMwMDBVj5CQkDTbLtIcHU0XgDKniRMnYtGiRYjbMbqWlha0tbXx5csXvHjxAi9evICrqyvmzJkDd3d3VK5cWYMl/s/du3dx7ty5BMe9fv1aGqdQKH56XTExMdJzuVz+08ujxN2+fVt6fuvWLQwZMiRF84WEhCA6Olr6/+vXr9LziIgIBAYGqk1vaGiY7DK9vb3VXvu4y/Dx8VEblzdvXpiamqaorD/iR/dLcooUKZImy1F5/fq19NzHxwelSpVKk+Veu3YNL1++TPDHwtWrV+Hj4wMTE5NUL7dBgwZ49OhRquapXbs2rl69mup1UebCGiOK5+bNm1i4cCGEEKhRowb+/fdfBAYGQi6XIyoqClFRUXj27BkWLVqEHDly4N27d7C3t9d0sTXi8ePH0vPUHEQHDBiA169fS49ly5ZJ444cOaI2rnDhwqkqU/369eHl5ZXsY9++fckua+3atWpl6dq1KwAgT548asMvXryYqjKm1p07dzBy5Ejp/w0bNmDDhg0pmrdjx44oUKCA9Ij7BbpixQq1cQUKFMClS5eSXWaDBg1QunRp6TFv3jxpXJMmTdTGTZgwIeUbmko/s186deoU7z0R93WsXbt2mpXT399frTZLdXz51YSHh6NChQqQyWSYM2eOVPuW2lpZIPZH2datW9G+fXsUKlQI+vr6yJ8/P+rWrQsnJyeEhYUlWIaE1qmrq4uCBQuidevW2L17d7x5jh49mmTZFi9eDAD4+PEjChQoAJlMhq1bt6b17sswDEYUT1BQkPR8+PDhaN26NfLnzy8N09XVRZkyZWBvb48yZcoAAD59+pTh5cwMnJ2dpednz57FnTt3UjRfnjx5YGlpKT1y5MghjcudO7c0vEiRIvj27Ru+fPmCL1++qNVEJObSpUtqX8yJPbp3757sslRBQvVQiYiIQNGiRaXhqQ1vKfXp0ydMnToVdevWxYcPH1C5cmX07dsXCoUCw4cPR5cuXZI9JZwdpcV+yZ07N0qVKqX2OH/+vDS+TZs2aVLW58+fo3nz5vj48SOMjIygpaWFkydPon///oiIiEiTdaSH27dvIyIiIkWPWrVqpWiZf/zxB548eYLq1atj8uTJP1y2ly9folq1arCzs8OxY8fw/v17REVFISgoCFevXsXkyZNRunRpXLlyJUXLi4mJwcePH3HixAn07t073mnwuN8J... (line truncated to 2000 chars)
1881:       "text/plain": [
1882:        "<Figure size 640x480 with 1 Axes>"
1883:       ]
1884:      },
1885:      "metadata": {},
1886:      "output_type": "display_data"
1887:     }
1888:    ],
1889:    "source": [
1890:     "boarding[['승차승객수','하차승객수']].head().plot(kind='bar', rot=45)                                 # boaring 에서 승차승객수 하차승객수만 뽑고 그것에서 상위 5개만 뽑고 이것을 플롯 차트 중 바 스타일로 시각화, (그리고 아래 텍스트는 45도 기울임)\n",
1891:     "plt.rc('font', family='Malgun Gothic')                                                               # 폰트 지정 기능인 rc 로 폰트를 맑은 고딕으로 지정함\n",
1892:     "plt.title('서울시 버스정류장 승하차 승객수 비교(TOP5)', fontsize=15, fontweight='bold', pad=15)       # 제목 지정 (그리고 크기, 굵기(넓정도) 그리고 자간 설정)\n",
1893:     "plt.xlabel('버스정류장', loc='right' )                                                  # x축 이름 지정(우측으로 위치 지정\n",
1894:     "plt.ylabel('승객 수(명)', loc='top')                                                                 # y축 이름 지정(상단으로 위치 지정\n",
1895:     "plt.show                                                                                             # 깔끔하게 시각화만 출력하기 위해 show를 쓴다."
1896:    ]
1897:   },
1898:   {
1899:    "cell_type": "code",
1900:    "execution_count": null,
1901:    "id": "6a26930c-800d-4f43-8f10-0bfc05619234",
1902:    "metadata": {},
1903:    "outputs": [],
1904:    "source": []
1905:   },
1906:   {
1907:    "cell_type": "code",
1908:    "execution_count": null,
1909:    "id": "3c7e6238-f1ed-4029-81c0-c4a5c7edee17",
1910:    "metadata": {},
1911:    "outputs": [],
1912:    "source": []
1913:   },
1914:   {
1915:    "cell_type": "code",
1916:    "execution_count": null,
1917:    "id": "07b29036-16ed-4cdf-842a-3cae91d6bde0",
1918:    "metadata": {},
1919:    "outputs": [],
1920:    "source": []
1921:   },
1922:   {
1923:    "cell_type": "code",
1924:    "execution_count": null,
1925:    "id": "2e0ef28a-7817-4c17-8cf3-a15d0ae7d96a",
1926:    "metadata": {},
1927:    "outputs": [],
1928:    "source": []
1929:   },
1930:   {
1931:    "cell_type": "code",
1932:    "execution_count": null,
1933:    "id": "75ba78a0-1803-4731-84b3-26c0d78e7ec6",
1934:    "metadata": {},
1935:    "outputs": [],
1936:    "source": []
1937:   },
1938:   {
1939:    "cell_type": "code",
1940:    "execution_count": null,
1941:    "id": "41fc9272-76ed-409c-abf1-42ab52fd3de9",
1942:    "metadata": {},
1943:    "outputs": [],
1944:    "source": []
1945:   },
1946:   {
1947:    "cell_type": "code",
1948:    "execution_count": null,
1949:    "id": "fc42464f-8c4a-4b99-8ffa-9c9a52d2392f",
1950:    "metadata": {},
1951:    "outputs": [],
1952:    "source": []
1953:   },
1954:   {
1955:    "cell_type": "code",
1956:    "execution_count": null,
1957:    "id": "8650813e-fd70-4971-b7da-14abdadcd39d",
1958:    "metadata": {},
1959:    "outputs": [],
1960:    "source": []
1961:   },
1962:   {
1963:    "cell_type": "code",
1964:    "execution_count": null,
1965:    "id": "c3decf9d-a63b-4276-bb09-9f8905de4d9e",
1966:    "metadata": {},
1967:    "outputs": [],
1968:    "source": []
1969:   },
1970:   {
1971:    "cell_type": "code",
1972:    "execution_count": null,
1973:    "id": "3da11b76-4a15-4db3-83a3-5bd84c6dcdb8",
1974:    "metadata": {},
1975:    "outputs": [],
1976:    "source": []
1977:   },
1978:   {
1979:    "cell_type": "code",
1980:    "execution_count": null,
1981:    "id": "beb77589-eb87-4fb2-bd27-aa40ccbd113d",
1982:    "metadata": {},
1983:    "outputs": [],
1984:    "source": []
1985:   },
1986:   {
1987:    "cell_type": "code",
1988:    "execution_count": null,
1989:    "id": "6c795bc3-8543-4369-a6bd-0b30ea75b3fd",
1990:    "metadata": {},
1991:    "outputs": [],
1992:    "source": []
1993:   },
1994:   {
1995:    "cell_type": "code",
1996:    "execution_count": null,
1997:    "id": "bec96446-bc87-4ddc-840c-e3d80cdb3944",
1998:    "metadata": {},
1999:    "outputs": [],
2000:    "source": []
2001:   },
2002:   {
2003:    "cell_type": "code",
2004:    "execution_count": null,
2005:    "id": "3f5bb1b6-c749-44bc-89db-81f18240b394",
2006:    "metadata": {},
2007:    "outputs": [],
2008:    "source": []
2009:   },
2010:   {
2011:    "cell_type": "code",
2012:    "execution_count": null,
2013:    "id": "9eabab64-ea7a-44cc-875a-f1f24768903b",
2014:    "metadata": {},
2015:    "outputs": [],
2016:    "source": []
2017:   },
2018:   {
2019:    "cell_type": "code",
2020:    "execution_count": null,
2021:    "id": "1d62b3b0-408e-4421-83c8-14de45a3d3b5",
2022:    "metadata": {},
2023:    "outputs": [],
2024:    "source": []
2025:   },
2026:   {
2027:    "cell_type": "code",
2028:    "execution_count": null,
2029:    "id": "13072074-c427-412e-8e0b-fab074f6240c",
2030:    "metadata": {},
2031:    "outputs": [],
2032:    "source": []
2033:   },
2034:   {
2035:    "cell_type": "code",
2036:    "execution_count": null,
2037:    "id": "96f915c4-7a7e-4b04-af3a-ad6734a47bff",
2038:    "metadata": {},
2039:    "outputs": [],
2040:    "source": []
2041:   },
2042:   {
2043:    "cell_type": "code",
2044:    "execution_count": null,
2045:    "id": "00ea35a7-3f56-4c9e-beb6-ee0f87d8febc",
2046:    "metadata": {},
2047:    "outputs": [],
2048:    "source": []
2049:   },
2050:   {
2051:    "cell_type": "code",
2052:    "execution_count": 130,
2053:    "id": "1a9c5136-39ff-45f8-bd1a-f6b6e8825db0",
2054:    "metadata": {},
2055:    "outputs": [],
2056:    "source": [
2057:     "import matplotlib.pyplot as plt       # 맷플롯리브 시각화\n",
2058:     "import pandas as pd                   # 판다스 데이터분석\n",
2059:     "import numpy as np                    # 넘파이 수학계산"
2060:    ]
2061:   },
2062:   {
2063:    "cell_type": "markdown",
2064:    "id": "1a6ed81f-e7e6-4de6-ba95-0fc0d315f510",
2065:    "metadata": {},
2066:    "source": [
2067:     "### 데이터를 만드는 법(코드에서)"
2068:    ]
2069:   },
2070:   {
2071:    "cell_type": "code",
2072:    "execution_count": 124,
2073:    "id": "4eeb1686-5dbf-4ac4-bd3d-26d75d1b41c1",
2074:    "metadata": {},
2075:    "outputs": [],
2076:    "source": [
2077:     "# 이것이 데이터 만드는 구조, 즉 템플릿이다.\n",
2078:     "\n",
2079:     "data = {\n",
2080:     "    '':[''],\n",
2081:     "    '':[''],\n",
2082:     "    '':[''],\n",
2083:     "    '':['']}"
2084:    ]
2085:   },
2086:   {
2087:    "cell_type": "code",
2088:    "execution_count": 124,
2089:    "id": "8df7c3a2",
2090:    "metadata": {},
2091:    "outputs": [],
2092:    "source": [
2093:     "# 실제로 이제 만들어본다.\n",
2094:     "\n",
2095:     "data = {\n",
2096:     "    'Name':['','','','','',''],\n",
2097:     "    'Dept':['','','','','',''],\n",
2098:     "    'Age':['','','','','',''],\n",
2099:     "    'Salary':['','','','','','']}"
2100:    ]
2101:   },
2102:   {
2103:    "cell_type": "code",
2104:    "execution_count": 126,
2105:    "id": "6aab5cc2",
2106:    "metadata": {},
2107:    "outputs": [],
2108:    "source": [
2109:     "# 실제로 이제 만들어본다. (값을 넣었다.)\n",
2110:     "# 그리고 Age의 3번째 np.nan의 np는 Numpy를 의미한다. 앞에서 Numpy 불러오기 및 별칭 지정을 선행했다.\n",
2111:     "\n",
2112:     "data = {\n",
2113:     "    'Name':['Choi','Kim','Lee','Pakr','Jung','Kang'],\n",
2114:     "    'Dept':['Sales','IT','IT','Sales','HR','IT'],\n",
2115:     "    'Age':['28','35','np.nan','31','40','np.nan'],\n",
2116:     "    'Salary':['3000','4500','3800','None','5000','4200']}"
2117:    ]
2118:   },
2119:   {
2120:    "cell_type": "code",
2121:    "execution_count": 153,
2122:    "id": "4cf16592-69d3-4e84-8c6a-6968e77b5861",
2123:    "metadata": {},
2124:    "outputs": [
2125:     {
2126:      "data": {
2127:       "text/html": [
2128:        "<div>\n",
2129:        "<style scoped>\n",
2130:        "    .dataframe tbody tr th:only-of-type {\n",
2131:        "        vertical-align: middle;\n",
2132:        "    }\n",
2133:        "\n",
2134:        "    .dataframe tbody tr th {\n",
2135:        "        vertical-align: top;\n",
2136:        "    }\n",
2137:        "\n",
2138:        "    .dataframe thead th {\n",
2139:        "        text-align: right;\n",
2140:        "    }\n",
2141:        "</style>\n",
2142:        "<table border=\"1\" class=\"dataframe\">\n",
2143:        "  <thead>\n",
2144:        "    <tr style=\"text-align: right;\">\n",
2145:        "      <th></th>\n",
2146:        "      <th>Name</th>\n",
2147:        "      <th>Dept</th>\n",
2148:        "      <th>Age</th>\n",
2149:        "      <th>Salary</th>\n",
2150:        "    </tr>\n",
2151:        "  </thead>\n",
2152:        "  <tbody>\n",
2153:        "    <tr>\n",
2154:        "      <th>0</th>\n",
2155:        "      <td>Choi</td>\n",
2156:        "      <td>Sales</td>\n",
2157:        "      <td>28.0</td>\n",
2158:        "      <td>3000.0</td>\n",
2159:        "    </tr>\n",
2160:        "    <tr>\n",
2161:        "      <th>1</th>\n",
2162:        "      <td>Kim</td>\n",
2163:        "      <td>IT</td>\n",
2164:        "      <td>35.0</td>\n",
2165:        "      <td>4500.0</td>\n",
2166:        "    </tr>\n",
2167:        "    <tr>\n",
2168:        "      <th>2</th>\n",
2169:        "      <td>Lee</td>\n",
2170:        "      <td>IT</td>\n",
2171:        "      <td>NaN</td>\n",
2172:        "      <td>3800.0</td>\n",
2173:        "    </tr>\n",
2174:        "    <tr>\n",
2175:        "      <th>3</th>\n",
2176:        "      <td>Pakr</td>\n",
2177:        "      <td>Sales</td>\n",
2178:        "      <td>31.0</td>\n",
2179:        "      <td>NaN</td>\n",
2180:        "    </tr>\n",
2181:        "    <tr>\n",
2182:        "      <th>4</th>\n",
2183:        "      <td>Jung</td>\n",
2184:        "      <td>HR</td>\n",
2185:        "      <td>40.0</td>\n",
2186:        "      <td>5000.0</td>\n",
2187:        "    </tr>\n",
2188:        "    <tr>\n",
2189:        "      <th>5</th>\n",
2190:        "      <td>Kang</td>\n",
2191:        "      <td>IT</td>\n",
2192:        "      <td>NaN</td>\n",
2193:        "      <td>4200.0</td>\n",
2194:        "    </tr>\n",
2195:        "  </tbody>\n",
2196:        "</table>\n",
2197:        "</div>"
2198:       ],
2199:       "text/plain": [
2200:        "   Name   Dept   Age  Salary\n",
2201:        "0  Choi  Sales  28.0  3000.0\n",
2202:        "1   Kim     IT  35.0  4500.0\n",
2203:        "2   Lee     IT   NaN  3800.0\n",
2204:        "3  Pakr  Sales  31.0     NaN\n",
2205:        "4  Jung     HR  40.0  5000.0\n",
2206:        "5  Kang     IT   NaN  4200.0"
2207:       ]
2208:      },
2209:      "execution_count": 153,
2210:      "metadata": {},
2211:      "output_type": "execute_result"
2212:     }
2213:    ],
2214:    "source": [
2215:     "data = {\n",
2216:     "    'Name':['Choi','Kim','Lee','Pakr','Jung','Kang'],\n",
2217:     "    'Dept':['Sales','IT','IT','Sales','HR','IT'],\n",
2218:     "    'Age':[28,35,np.nan,31,40,np.nan],               # NaN 나오게 하려면 나오게 할 부분은 따옴표로 감싸지 않으면 된다. (문자형으로 하지 말라.)\n",
2219:     "    'Salary':[3000,4500,3800,None,5000,4200]}\n",
2220:     "\n",
2221:     "df=pd.DataFrame(data)       # 데이터프레임 형식으로 바꾸어라는 코드이다.\n",
2222:     "df"
2223:    ]
2224:   },
2225:   {
2226:    "cell_type": "code",
2227:    "execution_count": 155,
2228:    "id": "e7cde9e7-0eaa-495d-9c36-7c6371970218",
2229:    "metadata": {},
2230:    "outputs": [
2231:     {
2232:      "data": {
2233:       "text/html": [
2234:        "<div>\n",
2235:        "<style scoped>\n",
2236:        "    .dataframe tbody tr th:only-of-type {\n",
2237:        "        vertical-align: middle;\n",
2238:        "    }\n",
2239:        "\n",
2240:        "    .dataframe tbody tr th {\n",
2241:        "        vertical-align: top;\n",
2242:        "    }\n",
2243:        "\n",
2244:        "    .dataframe thead th {\n",
2245:        "        text-align: right;\n",
2246:        "    }\n",
2247:        "</style>\n",
2248:        "<table border=\"1\" class=\"dataframe\">\n",
2249:        "  <thead>\n",
2250:        "    <tr style=\"text-align: right;\">\n",
2251:        "      <th></th>\n",
2252:        "      <th>Name</th>\n",
2253:        "      <th>Dept</th>\n",
2254:        "      <th>Salary</th>\n",
2255:        "    </tr>\n",
2256:        "  </thead>\n",
2257:        "  <tbody>\n",
2258:        "    <tr>\n",
2259:        "      <th>0</th>\n",
2260:        "      <td>Choi</td>\n",
2261:        "      <td>Sales</td>\n",
2262:        "      <td>3000.0</td>\n",
2263:        "    </tr>\n",
2264:        "    <tr>\n",
2265:        "      <th>1</th>\n",
2266:        "      <td>Kim</td>\n",
2267:        "      <td>IT</td>\n",
2268:        "      <td>4500.0</td>\n",
2269:        "    </tr>\n",
2270:        "    <tr>\n",
2271:        "      <th>2</th>\n",
2272:        "      <td>Lee</td>\n",
2273:        "      <td>IT</td>\n",
2274:        "      <td>3800.0</td>\n",
2275:        "    </tr>\n",
2276:        "    <tr>\n",
2277:        "      <th>3</th>\n",
2278:        "      <td>Pakr</td>\n",
2279:        "      <td>Sales</td>\n",
2280:        "      <td>NaN</td>\n",
2281:        "    </tr>\n",
2282:        "    <tr>\n",
2283:        "      <th>4</th>\n",
2284:        "      <td>Jung</td>\n",
2285:        "      <td>HR</td>\n",
2286:        "      <td>5000.0</td>\n",
2287:        "    </tr>\n",
2288:        "    <tr>\n",
2289:        "      <th>5</th>\n",
2290:        "      <td>Kang</td>\n",
2291:        "      <td>IT</td>\n",
2292:        "      <td>4200.0</td>\n",
2293:        "    </tr>\n",
2294:        "  </tbody>\n",
2295:        "</table>\n",
2296:        "</div>"
2297:       ],
2298:       "text/plain": [
2299:        "   Name   Dept  Salary\n",
2300:        "0  Choi  Sales  3000.0\n",
2301:        "1   Kim     IT  4500.0\n",
2302:        "2   Lee     IT  3800.0\n",
2303:        "3  Pakr  Sales     NaN\n",
2304:        "4  Jung     HR  5000.0\n",
2305:        "5  Kang     IT  4200.0"
2306:       ]
2307:      },
2308:      "execution_count": 155,
2309:      "metadata": {},
2310:      "output_type": "execute_result"
2311:     }
2312:    ],
2313:    "source": [
2314:     "df[['Name','Dept','Salary']]           # 이 3개 항목의 값들을 출력한다."
2315:    ]
2316:   },
2317:   {
2318:    "cell_type": "markdown",
2319:    "id": "1cb7dd24-6739-49d9-8423-4aff9eb9bc6e",
2320:    "metadata": {},
2321:    "source": [
2322:     "### 이제 조건을 달아 출력하거나, 특정 부분을 바꾼다."
2323:    ]
2324:   },
2325:   {
2326:    "cell_type": "code",
2327:    "execution_count": 156,
2328:    "id": "34beecd8-94dd-4e22-bfa3-05d72bc01c0c",
2329:    "metadata": {},
2330:    "outputs": [],
2331:    "source": [
2332:     "# 그런데, Dept가 IT인 것만 출력하고 싶다면?"
2333:    ]
2334:   },
2335:   {
2336:    "cell_type": "code",
2337:    "execution_count": 157,
2338:    "id": "eaa01780-2620-4867-9b19-9a1cfe78593e",
2339:    "metadata": {},
2340:    "outputs": [
2341:     {
2342:      "data": {
2343:       "text/html": [
2344:        "<div>\n",
2345:        "<style scoped>\n",
2346:        "    .dataframe tbody tr th:only-of-type {\n",
2347:        "        vertical-align: middle;\n",
2348:        "    }\n",
2349:        "\n",
2350:        "    .dataframe tbody tr th {\n",
2351:        "        vertical-align: top;\n",
2352:        "    }\n",
2353:        "\n",
2354:        "    .dataframe thead th {\n",
2355:        "        text-align: right;\n",
2356:        "    }\n",
2357:        "</style>\n",
2358:        "<table border=\"1\" class=\"dataframe\">\n",
2359:        "  <thead>\n",
2360:        "    <tr style=\"text-align: right;\">\n",
2361:        "      <th></th>\n",
2362:        "      <th>Name</th>\n",
2363:        "      <th>Salary</th>\n",
2364:        "    </tr>\n",
2365:        "  </thead>\n",
2366:        "  <tbody>\n",
2367:        "    <tr>\n",
2368:        "      <th>1</th>\n",
2369:        "      <td>Kim</td>\n",
2370:        "      <td>4500.0</td>\n",
2371:        "    </tr>\n",
2372:        "    <tr>\n",
2373:        "      <th>2</th>\n",
2374:        "      <td>Lee</td>\n",
2375:        "      <td>3800.0</td>\n",
2376:        "    </tr>\n",
2377:        "    <tr>\n",
2378:        "      <th>5</th>\n",
2379:        "      <td>Kang</td>\n",
2380:        "      <td>4200.0</td>\n",
2381:        "    </tr>\n",
2382:        "  </tbody>\n",
2383:        "</table>\n",
2384:        "</div>"
2385:       ],
2386:       "text/plain": [
2387:        "   Name  Salary\n",
2388:        "1   Kim  4500.0\n",
2389:        "2   Lee  3800.0\n",
2390:        "5  Kang  4200.0"
2391:       ]
2392:      },
2393:      "execution_count": 157,
2394:      "metadata": {},
2395:      "output_type": "execute_result"
2396:     }
2397:    ],
2398:    "source": [
2399:     "df.loc[df['Dept']=='IT',['Name','Salary']]        # Dept 이름이 IT이면 Name과 Salary를 출력하라."
2400:    ]
2401:   },
2402:   {
2403:    "cell_type": "code",
2404:    "execution_count": 158,
2405:    "id": "609fae41-dcdf-47c2-9bd0-91cbe633261d",
2406:    "metadata": {},
2407:    "outputs": [
2408:     {
2409:      "data": {
2410:       "text/html": [
2411:        "<div>\n",
2412:        "<style scoped>\n",
2413:        "    .dataframe tbody tr th:only-of-type {\n",
2414:        "        vertical-align: middle;\n",
2415:        "    }\n",
2416:        "\n",
2417:        "    .dataframe tbody tr th {\n",
2418:        "        vertical-align: top;\n",
2419:        "    }\n",
2420:        "\n",
2421:        "    .dataframe thead th {\n",
2422:        "        text-align: right;\n",
2423:        "    }\n",
2424:        "</style>\n",
2425:        "<table border=\"1\" class=\"dataframe\">\n",
2426:        "  <thead>\n",
2427:        "    <tr style=\"text-align: right;\">\n",
2428:        "      <th></th>\n",
2429:        "      <th>Name</th>\n",
2430:        "      <th>Dept</th>\n",
2431:        "      <th>Age</th>\n",
2432:        "      <th>Salary</th>\n",
2433:        "    </tr>\n",
2434:        "  </thead>\n",
2435:        "  <tbody>\n",
2436:        "    <tr>\n",
2437:        "      <th>0</th>\n",
2438:        "      <td>Choi</td>\n",
2439:        "      <td>Sales</td>\n",
2440:        "      <td>28.0</td>\n",
2441:        "      <td>3000.0</td>\n",
2442:        "    </tr>\n",
2443:        "    <tr>\n",
2444:        "      <th>1</th>\n",
2445:        "      <td>Kim</td>\n",
2446:        "      <td>IT</td>\n",
2447:        "      <td>35.0</td>\n",
2448:        "      <td>4500.0</td>\n",
2449:        "    </tr>\n",
2450:        "    <tr>\n",
2451:        "      <th>2</th>\n",
2452:        "      <td>Lee</td>\n",
2453:        "      <td>IT</td>\n",
2454:        "      <td>NaN</td>\n",
2455:        "      <td>3800.0</td>\n",
2456:        "    </tr>\n",
2457:        "    <tr>\n",
2458:        "      <th>3</th>\n",
2459:        "      <td>Pakr</td>\n",
2460:        "      <td>Sales</td>\n",
2461:        "      <td>31.0</td>\n",
2462:        "      <td>NaN</td>\n",
2463:        "    </tr>\n",
2464:        "    <tr>\n",
2465:        "      <th>4</th>\n",
2466:        "      <td>Jung</td>\n",
2467:        "      <td>HR</td>\n",
2468:        "      <td>40.0</td>\n",
2469:        "      <td>5000.0</td>\n",
2470:        "    </tr>\n",
2471:        "    <tr>\n",
2472:        "      <th>5</th>\n",
2473:        "      <td>Kang</td>\n",
2474:        "      <td>IT</td>\n",
2475:        "      <td>NaN</td>\n",
2476:        "      <td>4200.0</td>\n",
2477:        "    </tr>\n",
2478:        "  </tbody>\n",
2479:        "</table>\n",
2480:        "</div>"
2481:       ],
2482:       "text/plain": [
2483:        "   Name   Dept   Age  Salary\n",
2484:        "0  Choi  Sales  28.0  3000.0\n",
2485:        "1   Kim     IT  35.0  4500.0\n",
2486:        "2   Lee     IT   NaN  3800.0\n",
2487:        "3  Pakr  Sales  31.0     NaN\n",
2488:        "4  Jung     HR  40.0  5000.0\n",
2489:        "5  Kang     IT   NaN  4200.0"
2490:       ]
2491:      },
2492:      "execution_count": 158,
2493:      "metadata": {},
2494:      "output_type": "execute_result"
2495:     }
2496:    ],
2497:    "source": [
2498:     "df     # df를 출력. Nan은 다시 말하지만 공석 같은 것이다."
2499:    ]
2500:   },
2501:   {
2502:    "cell_type": "code",
2503:    "execution_count": 159,
2504:    "id": "ed78441d-806e-48b3-be8b-b7193fa70412",
2505:    "metadata": {},
2506:    "outputs": [
2507:     {
2508:      "data": {
2509:       "text/html": [
2510:        "<div>\n",
2511:        "<style scoped>\n",
2512:        "    .dataframe tbody tr th:only-of-type {\n",
2513:        "        vertical-align: middle;\n",
2514:        "    }\n",
2515:        "\n",
2516:        "    .dataframe tbody tr th {\n",
2517:        "        vertical-align: top;\n",
2518:        "    }\n",
2519:        "\n",
2520:        "    .dataframe thead th {\n",
2521:        "        text-align: right;\n",
2522:        "    }\n",
2523:        "</style>\n",
2524:        "<table border=\"1\" class=\"dataframe\">\n",
2525:        "  <thead>\n",
2526:        "    <tr style=\"text-align: right;\">\n",
2527:        "      <th></th>\n",
2528:        "      <th>Name</th>\n",
2529:        "      <th>Dept</th>\n",
2530:        "      <th>Age</th>\n",
2531:        "      <th>Salary</th>\n",
2532:        "    </tr>\n",
2533:        "  </thead>\n",
2534:        "  <tbody>\n",
2535:        "    <tr>\n",
2536:        "      <th>0</th>\n",
2537:        "      <td>Choi</td>\n",
2538:        "      <td>Sales</td>\n",
2539:        "      <td>28.0</td>\n",
2540:        "      <td>3000.0</td>\n",
2541:        "    </tr>\n",
2542:        "    <tr>\n",
2543:        "      <th>1</th>\n",
2544:        "      <td>Kim</td>\n",
2545:        "      <td>IT</td>\n",
2546:        "      <td>35.0</td>\n",
2547:        "      <td>4500.0</td>\n",
2548:        "    </tr>\n",
2549:        "    <tr>\n",
2550:        "      <th>2</th>\n",
2551:        "      <td>Lee</td>\n",
2552:        "      <td>IT</td>\n",
2553:        "      <td>33.5</td>\n",
2554:        "      <td>3800.0</td>\n",
2555:        "    </tr>\n",
2556:        "    <tr>\n",
2557:        "      <th>3</th>\n",
2558:        "      <td>Pakr</td>\n",
2559:        "      <td>Sales</td>\n",
2560:        "      <td>31.0</td>\n",
2561:        "      <td>NaN</td>\n",
2562:        "    </tr>\n",
2563:        "    <tr>\n",
2564:        "      <th>4</th>\n",
2565:        "      <td>Jung</td>\n",
2566:        "      <td>HR</td>\n",
2567:        "      <td>40.0</td>\n",
2568:        "      <td>5000.0</td>\n",
2569:        "    </tr>\n",
2570:        "    <tr>\n",
2571:        "      <th>5</th>\n",
2572:        "      <td>Kang</td>\n",
2573:        "      <td>IT</td>\n",
2574:        "      <td>33.5</td>\n",
2575:        "      <td>4200.0</td>\n",
2576:        "    </tr>\n",
2577:        "  </tbody>\n",
2578:        "</table>\n",
2579:        "</div>"
2580:       ],
2581:       "text/plain": [
2582:        "   Name   Dept   Age  Salary\n",
2583:        "0  Choi  Sales  28.0  3000.0\n",
2584:        "1   Kim     IT  35.0  4500.0\n",
2585:        "2   Lee     IT  33.5  3800.0\n",
2586:        "3  Pakr  Sales  31.0     NaN\n",
2587:        "4  Jung     HR  40.0  5000.0\n",
2588:        "5  Kang     IT  33.5  4200.0"
2589:       ]
2590:      },
2591:      "execution_count": 159,
2592:      "metadata": {},
2593:      "output_type": "execute_result"
2594:     }
2595:    ],
2596:    "source": [
2597:     "avg=df['Age'].mean()                # Age 의 평균을 구한다. mean은 평균을 의미한다.\n",
2598:     "df['Age']=df['Age'].fillna(avg)     # 데이터프레임에 Age에 이 avg 변수에 담긴 Age 평균을 담는다.\n",
2599:     "df                                 # 그리고 데이터프레임을 출력한다."
2600:    ]
2601:   },
2602:   {
2603:    "cell_type": "code",
2604:    "execution_count": 164,
2605:    "id": "3265552c-e708-4750-9612-7f6d8d82e4e6",
2606:    "metadata": {},
2607:    "outputs": [
2608:     {
2609:      "data": {
2610:       "text/html": [
2611:        "<div>\n",
2612:        "<style scoped>\n",
2613:        "    .dataframe tbody tr th:only-of-type {\n",
2614:        "        vertical-align: middle;\n",
2615:        "    }\n",
2616:        "\n",
2617:        "    .dataframe tbody tr th {\n",
2618:        "        vertical-align: top;\n",
2619:        "    }\n",
2620:        "\n",
2621:        "    .dataframe thead th {\n",
2622:        "        text-align: right;\n",
2623:        "    }\n",
2624:        "</style>\n",
2625:        "<table border=\"1\" class=\"dataframe\">\n",
2626:        "  <thead>\n",
2627:        "    <tr style=\"text-align: right;\">\n",
2628:        "      <th></th>\n",
2629:        "      <th>Name</th>\n",
2630:        "      <th>Dept</th>\n",
2631:        "      <th>Age</th>\n",
2632:        "      <th>Salary</th>\n",
2633:        "    </tr>\n",
2634:        "  </thead>\n",
2635:        "  <tbody>\n",
2636:        "    <tr>\n",
2637:        "      <th>0</th>\n",
2638:        "      <td>Choi</td>\n",
2639:        "      <td>Sales</td>\n",
2640:        "      <td>28.0</td>\n",
2641:        "      <td>3000.0</td>\n",
2642:        "    </tr>\n",
2643:        "    <tr>\n",
2644:        "      <th>1</th>\n",
2645:        "      <td>Kim</td>\n",
2646:        "      <td>IT</td>\n",
2647:        "      <td>35.0</td>\n",
2648:        "      <td>4500.0</td>\n",
2649:        "    </tr>\n",
2650:        "    <tr>\n",
2651:        "      <th>2</th>\n",
2652:        "      <td>Lee</td>\n",
2653:        "      <td>IT</td>\n",
2654:        "      <td>33.5</td>\n",
2655:        "      <td>3800.0</td>\n",
2656:        "    </tr>\n",
2657:        "    <tr>\n",
2658:        "      <th>4</th>\n",
2659:        "      <td>Jung</td>\n",
2660:        "      <td>HR</td>\n",
2661:        "      <td>40.0</td>\n",
2662:        "      <td>5000.0</td>\n",
2663:        "    </tr>\n",
2664:        "    <tr>\n",
2665:        "      <th>5</th>\n",
2666:        "      <td>Kang</td>\n",
2667:        "      <td>IT</td>\n",
2668:        "      <td>33.5</td>\n",
2669:        "      <td>4200.0</td>\n",
2670:        "    </tr>\n",
2671:        "  </tbody>\n",
2672:        "</table>\n",
2673:        "</div>"
2674:       ],
2675:       "text/plain": [
2676:        "   Name   Dept   Age  Salary\n",
2677:        "0  Choi  Sales  28.0  3000.0\n",
2678:        "1   Kim     IT  35.0  4500.0\n",
2679:        "2   Lee     IT  33.5  3800.0\n",
2680:        "4  Jung     HR  40.0  5000.0\n",
2681:        "5  Kang     IT  33.5  4200.0"
2682:       ]
2683:      },
2684:      "execution_count": 164,
2685:      "metadata": {},
2686:      "output_type": "execute_result"
2687:     }
2688:    ],
2689:    "source": [
2690:     "df_cleaned=df.dropna(subset=['Salary'])           # Nan을 drop한다. 즉 지운다. 그리고 그것을 df_cleaned 변수에 저장한다.    (dropna 명령어 기능)\n",
2691:     "df_cleaned                                        # 그리고 df_cleanded 변수를 출력한다."
2692:    ]
2693:   },
2694:   {
2695:    "cell_type": "markdown",
2696:    "id": "11922f2e-f085-426e-b873-d06fabb19caf",
2697:    "metadata": {},
2698:    "source": [
2699:     "### 그룹핑(Grouping)?, =그룹바이 =groupby"
2700:    ]
2701:   },
2702:   {
2703:    "cell_type": "code",
2704:    "execution_count": 165,
2705:    "id": "3b384d9f-a777-4705-b442-075dcfa9dba1",
2706:    "metadata": {},
2707:    "outputs": [
2708:     {
2709:      "data": {
2710:       "text/html": [
2711:        "<div>\n",
2712:        "<style scoped>\n",
2713:        "    .dataframe tbody tr th:only-of-type {\n",
2714:        "        vertical-align: middle;\n",
2715:        "    }\n",
2716:        "\n",
2717:        "    .dataframe tbody tr th {\n",
2718:        "        vertical-align: top;\n",
2719:        "    }\n",
2720:        "\n",
2721:        "    .dataframe thead th {\n",
2722:        "        text-align: right;\n",
2723:        "    }\n",
2724:        "</style>\n",
2725:        "<table border=\"1\" class=\"dataframe\">\n",
2726:        "  <thead>\n",
2727:        "    <tr style=\"text-align: right;\">\n",
2728:        "      <th></th>\n",
2729:        "      <th>Dept</th>\n",
2730:        "      <th>Salary</th>\n",
2731:        "      <th>Age</th>\n",
2732:        "    </tr>\n",
2733:        "  </thead>\n",
2734:        "  <tbody>\n",
2735:        "    <tr>\n",
2736:        "      <th>0</th>\n",
2737:        "      <td>Sales</td>\n",
2738:        "      <td>3000.0</td>\n",
2739:        "      <td>28.0</td>\n",
2740:        "    </tr>\n",
2741:        "    <tr>\n",
2742:        "      <th>1</th>\n",
2743:        "      <td>IT</td>\n",
2744:        "      <td>4500.0</td>\n",
2745:        "      <td>35.0</td>\n",
2746:        "    </tr>\n",
2747:        "    <tr>\n",
2748:        "      <th>2</th>\n",
2749:        "      <td>IT</td>\n",
2750:        "      <td>3800.0</td>\n",
2751:        "      <td>33.5</td>\n",
2752:        "    </tr>\n",
2753:        "    <tr>\n",
2754:        "      <th>4</th>\n",
2755:        "      <td>HR</td>\n",
2756:        "      <td>5000.0</td>\n",
2757:        "      <td>40.0</td>\n",
2758:        "    </tr>\n",
2759:        "    <tr>\n",
2760:        "      <th>5</th>\n",
2761:        "      <td>IT</td>\n",
2762:        "      <td>4200.0</td>\n",
2763:        "      <td>33.5</td>\n",
2764:        "    </tr>\n",
2765:        "  </tbody>\n",
2766:        "</table>\n",
2767:        "</div>"
2768:       ],
2769:       "text/plain": [
2770:        "    Dept  Salary   Age\n",
2771:        "0  Sales  3000.0  28.0\n",
2772:        "1     IT  4500.0  35.0\n",
2773:        "2     IT  3800.0  33.5\n",
2774:        "4     HR  5000.0  40.0\n",
2775:        "5     IT  4200.0  33.5"
2776:       ]
2777:      },
2778:      "execution_count": 165,
2779:      "metadata": {},
2780:      "output_type": "execute_result"
2781:     }
2782:    ],
2783:    "source": [
2784:     "df_cleaned[['Dept','Salary','Age']]"
2785:    ]
2786:   },
2787:   {
2788:    "cell_type": "markdown",
2789:    "id": "8a69c58f-5a4e-4edb-b33e-3e9ba6e57575",
2790:    "metadata": {},
2791:    "source": [
2792:     "### =그룹바이 =groupby"
2793:    ]
2794:   },
2795:   {
2796:    "cell_type": "code",
2797:    "execution_count": 179,
2798:    "id": "f08d894c-693f-4b4a-b555-6dc3261f69b2",
2799:    "metadata": {},
2800:    "outputs": [
2801:     {
2802:      "data": {
2803:       "text/html": [
2804:        "<div>\n",
2805:        "<style scoped>\n",
2806:        "    .dataframe tbody tr th:only-of-type {\n",
2807:        "        vertical-align: middle;\n",
2808:        "    }\n",
2809:        "\n",
2810:        "    .dataframe tbody tr th {\n",
2811:        "        vertical-align: top;\n",
2812:        "    }\n",
2813:        "\n",
2814:        "    .dataframe thead th {\n",
2815:        "        text-align: right;\n",
2816:        "    }\n",
2817:        "</style>\n",
2818:        "<table border=\"1\" class=\"dataframe\">\n",
2819:        "  <thead>\n",
2820:        "    <tr style=\"text-align: right;\">\n",
2821:        "      <th></th>\n",
2822:        "      <th>Salary</th>\n",
2823:        "      <th>Age</th>\n",
2824:        "    </tr>\n",
2825:        "    <tr>\n",
2826:        "      <th>Dept</th>\n",
2827:        "      <th></th>\n",
2828:        "      <th></th>\n",
2829:        "    </tr>\n",
2830:        "  </thead>\n",
2831:        "  <tbody>\n",
2832:        "    <tr>\n",
2833:        "      <th>HR</th>\n",
2834:        "      <td>5000.000000</td>\n",
2835:        "      <td>40.0</td>\n",
2836:        "    </tr>\n",
2837:        "    <tr>\n",
2838:        "      <th>IT</th>\n",
2839:        "      <td>4166.666667</td>\n",
2840:        "      <td>34.0</td>\n",
2841:        "    </tr>\n",
2842:        "    <tr>\n",
2843:        "      <th>Sales</th>\n",
2844:        "      <td>3000.000000</td>\n",
2845:        "      <td>28.0</td>\n",
2846:        "    </tr>\n",
2847:        "  </tbody>\n",
2848:        "</table>\n",
2849:        "</div>"
2850:       ],
2851:       "text/plain": [
2852:        "            Salary   Age\n",
2853:        "Dept                    \n",
2854:        "HR     5000.000000  40.0\n",
2855:        "IT     4166.666667  34.0\n",
2856:        "Sales  3000.000000  28.0"
2857:       ]
2858:      },
2859:      "execution_count": 179,
2860:      "metadata": {},
2861:      "output_type": "execute_result"
2862:     }
2863:    ],
2864:    "source": [
2865:     "df_cleaned[['Dept','Salary','Age']].groupby('Dept')[['Salary','Age']].mean()   # Dept로 그룹바이를 하고 mean 즉 평균을 구한다. Salary와 Age도 명시해서 Dept로\n",
2866:     "                                                                               # 그룹바이를 하고 Salary와 Age의 평균 값을 구하라는 구체적이고 명시적인 Query가 완성된다\n",
2867:     "                                                                               # Dept 기준으로 그룹바이함"
2868:    ]
2869:   },
2870:   {
2871:    "cell_type": "code",
2872:    "execution_count": 170,
2873:    "id": "70b46c08",
2874:    "metadata": {},
2875:    "outputs": [
2876:     {
2877:      "data": {
2878:       "text/plain": [
2879:        "<Axes: xlabel='Dept'>"
2880:       ]
2881:      },
2882:      "execution_count": 170,
2883:      "metadata": {},
2884:      "output_type": "execute_result"
2885:     },
2886:     {
2887:      "data": {
2888:       "image/png": "iVBORw0KGgoAAAANSUhEUgAAAiwAAAHBCAYAAABKReAoAAAAOnRFWHRTb2Z0d2FyZQBNYXRwbG90bGliIHZlcnNpb24zLjEwLjAsIGh0dHBzOi8vbWF0cGxvdGxpYi5vcmcvlHJYcgAAAAlwSFlzAAAPYQAAD2EBqD+naQAAKlJJREFUeJzt3XtU1Ped//HX4CgKyq14AcRBxWtMzEoFrSfaJuZktynRxGA2ujRZdyUGY9A2N3SrEN2qXWLcxlbTVruS1Fsia8R4uqwa060S0UYTo6EmKKDiBRhuriIyM78/bObXWUBFkfkAz8c5c074fr7f4f1NpvXpzHdmLC6XyyUAAACD+Xh7AAAAgJshWAAAgPEIFgAAYDyCBQAAGI9gAQAAxiNYAACA8QgWAABgPIIFAAAYz+rtAVqC0+lUSUmJevToIYvF4u1xAADALXC5XKqpqVF4eLh8fG78HEq7CJaSkhJFRkZ6ewwAAHAbTp8+rb59+95wn3YRLD169JB0/YQDAgK8PA0AALgV1dXVioyMdP85fiPtIli+eRkoICCAYAEAoI25lcs5uOgWAAAYj2ABAADGI1gAAIDx2sU1LAAAtASHw6Fr1655e4x2o1OnTrJarS3ykSMECwAAki5duqQzZ87I5XJ5e5R2xc/PT2FhYerSpcsd3Q/BAgDo8BwOh86cOSM/Pz/17NmTDyFtAS6XS3V1dSotLdWpU6c0aNCgm3443I0QLACADu/atWtyuVzq2bOnunXr5u1x2o1u3bqpc+fOKioqUl1dnbp27Xrb98VFtwAA/AXPrLS8O3lWxeN+WuReAAAA7iJeEgIAoAlRr33Yqr+vcNmjrfr72pJmPcPy5ptvKjAwUFFRUe5bQUGBJOnw4cMaM2aMbDabhg8frpycHI9jV65cqejoaEVERGjy5MkqKytzr5WXlyshIUH9+vWTzWZTRkZGC5waAADt38WLFzVr1iwNGzZMERER6tOnj957770bHlNYWHhH15N4Q7OCpaKiQnPnzlVhYaH7NnDgQNXU1Cg+Pl5LlixRUVGR1qxZo6lTp+r8+fOSpC1btigzM1N5eXkqLi5WWFiYkpKS3PebmJioESNGqKioSLm5uVq1apWys7Nb9kwBAGiHHnvsMQ0fPlzHjh3T2bNn9fnnn2vEiBHeHqvFNStY7Ha7goKCGmzfuHGjRo8erYkTJ0qSxo8frwkTJmjz5s2Srj+7smjRIoWEhKhTp05avHixduzYIbvdrhMnTujgwYNasGCBLBaLwsPDlZKSonXr1t352QEA0I7Z7Xbl5eVp1qxZ7otbe/XqpWHDhnl5spbX7GdYGguW3NxcjRs3zmNbbGysjhw5ovr6eh06dMhjPTQ0VDabTUePHlVubq7i4uJktVobHNuUq1evqrq62uMGAEBHExQUpPDwcP3Lv/yL6uvrPdbKy8s1bdo0RUVFKTIyUvHx8SovL2/0fnbt2uW+rMNms+nf/u3f3GtpaWn653/+Z02fPl3h4eH64osv9Dd/8zfasGGDx31MnTpVP//5z1v+JP+iWRfdVlRUaMGCBVq4cKEGDRqkBQsW6KGHHlJJSYkefPBBj3179eqlAwcOqLS0VA6HQ6GhoQ3Wy8vLVVJSot69eze61pSlS5cqPT29OaMbo7Uv4LodXPQFAG2Dj4+PduzYoYSEBGVlZSk9PV3Tpk2TxWLRpUuXNHXqVL3zzjuSpCeffFIZGRlaunRpg/u5fPmy3n33XUVHR6u4uFgjRoxQfHy8hg4dKkn64IMPtG3bNv3ud7+T0+nUrFmztH79ek2bNk2SVFZWpt27d+vXv/713TvX5uy8Y8cOlZSU6NSpU5ozZ46eeOIJffrpp3I4HA0+ytjhcMhiscjhcEjSDdebWmtKamqqqqqq3LfTp0835zQAAGg37r//fh07dkzJycmaO3euvve976miokI2m02TJ09WeXm5PvnkE4WEhOjYsWON3sdj... (line truncated to 2000 chars)
2889:       "text/plain": [
2890:        "<Figure size 640x480 with 1 Axes>"
2891:       ]
2892:      },
2893:      "metadata": {},
2894:      "output_type": "display_data"
2895:     }
2896:    ],
2897:    "source": [
2898:     "df_cleaned[['Dept','Salary','Age']].groupby('Dept')[['Salary','Age']].mean().plot(kind='bar')       # plot(kind='bar')  붙이니 바로 그래프 생성이 되는 모습이다."
2899:    ]
2900:   },
2901:   {
2902:    "cell_type": "code",
2903:    "execution_count": 171,
2904:    "id": "0e3b8f09-5e46-4d38-b49c-828f09cf8a61",
2905:    "metadata": {},
2906:    "outputs": [
2907:     {
2908:      "data": {
2909:       "text/plain": [
2910:        "<Axes: xlabel='Dept'>"
2911:       ]
2912:      },
2913:      "execution_count": 171,
2914:      "metadata": {},
2915:      "output_type": "execute_result"
2916:     },
2917:     {
2918:      "data": {
2919:       "image/png": "iVBORw0KGgoAAAANSUhEUgAAAiwAAAHBCAYAAABKReAoAAAAOnRFWHRTb2Z0d2FyZQBNYXRwbG90bGliIHZlcnNpb24zLjEwLjAsIGh0dHBzOi8vbWF0cGxvdGxpYi5vcmcvlHJYcgAAAAlwSFlzAAAPYQAAD2EBqD+naQAAKlJJREFUeJzt3XtU1Ped//HX4CgKyq14AcRBxWtMzEoFrSfaJuZktynRxGA2ujRZdyUGY9A2N3SrEN2qXWLcxlbTVruS1Fsia8R4uqwa060S0UYTo6EmKKDiBRhuriIyM78/bObXWUBFkfkAz8c5c074fr7f4f1NpvXpzHdmLC6XyyUAAACD+Xh7AAAAgJshWAAAgPEIFgAAYDyCBQAAGI9gAQAAxiNYAACA8QgWAABgPIIFAAAYz+rtAVqC0+lUSUmJevToIYvF4u1xAADALXC5XKqpqVF4eLh8fG78HEq7CJaSkhJFRkZ6ewwAAHAbTp8+rb59+95wn3YRLD169JB0/YQDAgK8PA0AALgV1dXVioyMdP85fiPtIli+eRkoICCAYAEAoI25lcs5uOgWAAAYj2ABAADGI1gAAIDx2sU1LAAAtASHw6Fr1655e4x2o1OnTrJarS3ykSMECwAAki5duqQzZ87I5XJ5e5R2xc/PT2FhYerSpcsd3Q/BAgDo8BwOh86cOSM/Pz/17NmTDyFtAS6XS3V1dSotLdWpU6c0aNCgm3443I0QLACADu/atWtyuVzq2bOnunXr5u1x2o1u3bqpc+fOKioqUl1dnbp27Xrb98VFtwAA/AXPrLS8O3lWxeN+WuReAAAA7iJeEgIAoAlRr33Yqr+vcNmjrfr72pJmPcPy5ptvKjAwUFFRUe5bQUGBJOnw4cMaM2aMbDabhg8frpycHI9jV65cqejoaEVERGjy5MkqKytzr5WXlyshIUH9+vWTzWZTRkZGC5waAADt38WLFzVr1iwNGzZMERER6tOnj957770bHlNYWHhH15N4Q7OCpaKiQnPnzlVhYaH7NnDgQNXU1Cg+Pl5LlixRUVGR1qxZo6lTp+r8+fOSpC1btigzM1N5eXkqLi5WWFiYkpKS3PebmJioESNGqKioSLm5uVq1apWys7Nb9kwBAGiHHnvsMQ0fPlzHjh3T2bNn9fnnn2vEiBHeHqvFNStY7Ha7goKCGmzfuHGjRo8erYkTJ0qSxo8frwkTJmjz5s2Srj+7smjRIoWEhKhTp05avHixduzYIbvdrhMnTujgwYNasGCBLBaLwsPDlZKSonXr1t352QEA0I7Z7Xbl5eVp1qxZ7otbe/XqpWHDhnl5spbX7GdYGguW3NxcjRs3zmNbbGysjhw5ovr6eh06dMhjPTQ0VDabTUePHlVubq7i4uJktVobHNuUq1evqrq62uMGAEBHExQUpPDwcP3Lv/yL6uvrPdbKy8s1bdo0RUVFKTIyUvHx8SovL2/0fnbt2uW+rMNms+nf/u3f3GtpaWn653/+Z02fPl3h4eH64osv9Dd/8zfasGGDx31MnTpVP//5z1v+JP+iWRfdVlRUaMGCBVq4cKEGDRqkBQsW6KGHHlJJSYkefPBBj3179eqlAwcOqLS0VA6HQ6GhoQ3Wy8vLVVJSot69eze61pSlS5cqPT29OaMbo7Uv4LodXPQFAG2Dj4+PduzYoYSEBGVlZSk9PV3Tpk2TxWLRpUuXNHXqVL3zzjuSpCeffFIZGRlaunRpg/u5fPmy3n33XUVHR6u4uFgjRoxQfHy8hg4dKkn64IMPtG3bNv3ud7+T0+nUrFmztH79ek2bNk2SVFZWpt27d+vXv/713TvX5uy8Y8cOlZSU6NSpU5ozZ46eeOIJffrpp3I4HA0+ytjhcMhiscjhcEjSDdebWmtKamqqqqqq3LfTp0835zQAAGg37r//fh07dkzJycmaO3euvve976miokI2m02TJ09WeXm5PvnkE4WEhOjYsWON3sdj... (line truncated to 2000 chars)
2920:       "text/plain": [
2921:        "<Figure size 640x480 with 1 Axes>"
2922:       ]
2923:      },
2924:      "metadata": {},
2925:      "output_type": "display_data"
2926:     }
2927:    ],
2928:    "source": [
2929:     "df_gr=df_cleaned[['Dept','Salary','Age']].groupby('Dept')[['Salary','Age']].mean()\n",
2930:     "df_gr.plot(kind='bar')      # 이렇게 하면 한줄에 너무 길지 않아서 편하다. 변수 할당 방식이다."
2931:    ]
2932:   },
2933:   {
2934:    "cell_type": "code",
2935:    "execution_count": 177,
2936:    "id": "bf8b03f4-de5c-4c49-af4c-6c51c74ac513",
2937:    "metadata": {},
2938:    "outputs": [
2939:     {
2940:      "data": {
2941:       "text/plain": [
2942:        "<Axes: xlabel='Dept'>"
2943:       ]

(Output capped at 50 KB. Showing lines 1418-2943. Use offset=2944 to continue.)
</content>
```

---

## Assistant (Build · DeepSeek V4 Flash Free · 17.9s)

_Thinking:_

I've now read all the key files. Let me summarize what I've found and provide coaching to the user.

The competition is:
- **2026 경운대학교 지능형모빌리티 소프트웨어 경진대회 (July 20-21)**
- So the competition is tomorrow and the day after!

The practice notebooks show:
1. **20260704-토요실습1.ipynb** - Covers basic pandas operations on `seoul_traffic_202605.xlsx` (bus_station sheet):
   - Reading Excel files with `pd.read_excel()`
   - Selecting columns with double brackets `df[['col1','col2']]`
   - Using `.head()` to view top rows
   - Using `.iloc[]` for integer-based indexing and `.loc[]` for label-based indexing
   - Sorting with `.sort_values(by='col', ascending=True/False)`
   - Setting index with `df.index = df['column']`
   - Plotting with `df.plot(kind='bar')`

2. **20260705-일요실습1.ipynb** - Continues with more pandas operations:
   - Adding new columns: `df['new_col'] = df['col1'] + df['col2']`
   - GroupBy: `df.groupby('col').sum()`
   - Sorting grouped results: `.sort_values(by='col', ascending=False).head(5)`
   - Multiple types of plots: bar, line, barh
   - Customizing plots with matplotlib (title, xlabel, ylabel, font)
   - There's an error at the end where they tried to select columns that don't exist (경인선, 경의선, etc.)

3. **20260719-일요실습1.ipynb** - This is basically a copy of the 0704 notebook with nothing new added, just more empty cells. The user admits: "(사실 0704 토요실습 파일 그대로 복사된것...) (오늘이 19인데 별로 안했단 것...)" 

So the user hasn't really progressed much since the 4th and 5th. The competition is in 1-2 days.

The key topics they've practiced:
- pandas: read_excel, selecting columns, loc/iloc, sort_values, indexing, adding columns, groupby, handling NaN
- matplotlib: bar, line, barh plots, title, labels, font settings
- Creating DataFrames from scratch with dicts

What they might need to focus on:
1. Data cleaning (handling missing values) - they covered some with fillna and dropna
2. GroupBy operations - covered well
3. Merging/joining datasets
4. More visualization types (scatter, histogram, etc.)
5. Statistical summaries (describe, etc.)
6. File I/O (different formats)

Let me give them some focused coaching.

자, 다 봤다. 상황 정리:

**대회: 7/20(월)~7/21(화) — 내일 모레다.**

**현재 학습 상태:**
- 7/4 토요실습: pandas 기초 (읽기, 선택, 정렬, loc/iloc, index 설정, plot)
- 7/5 일요실습: groupby, 새 컬럼 추가, sort_values 후 head, bar/line/barh 그래프, 한글 폰트 설정
- 7/19 오늘 파일: **7/4 파일 그대로 복붙, 빈 셀만 늘어남** (본인 인정)

**가장 큰 문제:** 7/5 이후로 **진전이 전혀 없다**. 오늘까지 2주를 날렸다.

**핵심 코칭:**

1. **당장 오늘 해야 할 것** — 실습 파일 다시从头 돌려봐라. 코드를 **직접 치면서** 이해해야 한다. 복붙만 하면 대회에서 못 쓴다.

2. **추가로 꼭 익혀야 할 것 (시험에 나올 가능성 높음):**
   - `merge()` / `concat()` — 두 데이터프레임 합치기
   - `df.describe()`, `df.info()`, `df.isnull().sum()` — 데이터 탐색
   - `df.groupby().agg({'col': ['sum','mean','count']})` — 여러 통계 한번에
   - `pd.read_csv()` — csv 파일 읽기 (데이터셋 대부분이 csv다)
   - 조건 필터링: `df[df['col'] > 100]` — 이미 살짝 함
   - `value_counts()`, `unique()` — 범주형 데이터 탐색

3. **데이터 파일 중 문제에서 쓰일 만한 것들:**
   - `seoul_traffic_202605.xlsx` — 실습에서 썼고, sheet_name= 매개변수 중요
   - `iris.csv`, `covid.csv`, `bank.csv`, `customers.csv`, `nba.csv`, `netflix.csv`, `titanic(없지만)`
   - **대부분 csv 파일**이므로 `pd.read_csv()` 위주로 연습

4. **실전 전략:**
   - 대회 시작하면 **일단 모든 데이터셋을 `df.head()`, `df.info()`, `df.describe()` 로 탐색**하라
   - 결측치부터 처리하고 (`fillna` 또는 `dropna`)
   - 문제에서 요구하는 출력 형태를 먼저 파악하라

**지금 당장 할 것:** 7/5 일요실습 마지막에 난 에러 (`KeyError: 경인선...`) 고치는 것부터 시작해라. 그게 오늘 한 일 중 유일하게 의미 있는 출발점이다.

---

## User

너가 문제좀 지금 내볼래? ㅠㅠ 그냥 좀 해보게.. 데이터셋 어떤게 나올진 모르지 ㅋㅋㅋ ㅠㅠㅠ키에러 그건 모르겠다

---

## Assistant (Build · DeepSeek V4 Flash Free · 7.6s)

_Thinking:_

The user wants me to create practice problems based on the datasets available. Let me think about what kinds of problems would be realistic for this competition.

Let me look at a few more of the datasets to understand what's available, then create some practice problems.

Actually, I already have a good idea of the datasets. Let me create some problems. But I should also fix that KeyError they're stuck on. And I should look at some of the csv files to know what columns they have.

Let me check a few key datasets to make good problems.

일단 에러부터 고치고, 바로 문제 내줄게. 데이터 좀 더 확인하고.

**Tool: bash**

**Input:**
```json
{
  "command": "Get-Content \"C:\\Users\\Administrator\\Documents\\GitHub\\kw-competition-practice\\iris.csv\" -Head 3"
}
```

**Output:**
```
sepal_length,sepal_width,petal_length,petal_width,species
5.1,3.5,1.4,0.2,setosa
4.9,3,1.4,0.2,setosa

```

**Tool: bash**

**Input:**
```json
{
  "command": "Get-Content \"C:\\Users\\Administrator\\Documents\\GitHub\\kw-competition-practice\\covid.csv\" -Head 3"
}
```

**Output:**
```
�׸�,��ʼ�,����,����,��ȭ����
����Ʈ��,999,78.9,1.7,19.4
�ڷ�����,965,68.5,3.9,27.6

```

**Tool: bash**

**Input:**
```json
{
  "command": "Get-Content \"C:\\Users\\Administrator\\Documents\\GitHub\\kw-competition-practice\\netflix.csv\" -Head 3"
}
```

**Output:**
```
title,director,date_added,type
Alias Grace,,3-Nov-17,TV Show
A Patch of Fog,Michael Lennox,15-Apr-17,Movie

```

**Tool: bash**

**Input:**
```json
{
  "command": "Get-Content \"C:\\Users\\Administrator\\Documents\\GitHub\\kw-competition-practice\\customers.csv\" -Head 3"
}
```

**Output:**
```
Name,Address
Frank Manning,"6461 Quinn Groves, East Matthew, New Hampshire, 16656"
Elizabeth Johnson,"1360 Tracey Ports Apt. 419, Kyleport, Vermont, 31924"

```

**Tool: bash**

**Input:**
```json
{
  "command": "Get-Content \"C:\\Users\\Administrator\\Documents\\GitHub\\kw-competition-practice\\bank.csv\" -Head 3"
}
```

**Output:**
```
job,education,balance,duration,y
management,tertiary,2143,261,no
technician,secondary,265,348,no

```

**Tool: bash**

**Input:**
```json
{
  "command": "Get-Content \"C:\\Users\\Administrator\\Documents\\GitHub\\kw-competition-practice\\used_cars.csv\" -Head 3"
}
```

**Output:**
```
Manufacturer,Year,Fuel,Transmission,Price
Acura,2012,Gas,Automatic,10299
Jaguar,2011,Gas,Automatic,9500

```

---

## Assistant (Build · DeepSeek V4 Flash Free · 4.4s)

_Thinking:_

Now let me also check a few more datasets to give diverse problems.

**Tool: bash**

**Input:**
```json
{
  "command": "Get-Content \"C:\\Users\\Administrator\\Documents\\GitHub\\kw-competition-practice\\sales_by_employee.csv\" -Head 3; echo \"---\"; Get-Content \"C:\\Users\\Administrator\\Documents\\GitHub\\kw-competition-practice\\weather.csv\" -Head 3; echo \"---\"; Get-Content \"C:\\Users\\Administrator\\Documents\\GitHub\\kw-competition-practice\\pokemon.csv\" -Head 3; echo \"---\"; Get-Content \"C:\\Users\\Administrator\\Documents\\GitHub\\kw-competition-practice\\movies.csv\" -Head 3; echo \"---\"; Get-Content \"C:\\Users\\Administrator\\Documents\\GitHub\\kw-competition-practice\\fortune1000.csv\" -Head 3; echo \"---\"; Get-Content \"C:\\Users\\Administrator\\Documents\\GitHub\\kw-competition-practice\\nba.csv\" -Head 3"
}
```

**Output:**
```
Date,Name,Customer,Revenue,Expenses
1/1/20,Oscar,Logistics XYZ,5250,531
1/1/20,Oscar,Money Corp.,4406,661
---
date,temp,max_wind,mean_wind
2010-08-01,28.7,8.3,3.4
2010-08-02,25.2,8.7,3.8
---
Pokemon,Type
Bulbasaur,Grass / Poison
Ivysaur,Grass / Poison
---
Rank,Title,Studio,Gross,Year
1,Avengers: Endgame,Buena Vista,"$2,796.30 ",2019
2,Avatar,Fox,"$2,789.70 ",2009
---
Company,Revenues,Profits,Employees,Sector,Industry
Walmart,500343,9862,2300000,Retailing,General Merchandisers
Exxon Mobil,244363,19710,71200,Energy,Petroleum Refining
---
Name,Team,Position,Birthday,Salary
Shake Milton,Philadelphia 76ers,SG,9/26/96,1445697
Christian Wood,Detroit Pistons,PF,9/27/95,1645357

```

---

## Assistant (Build · DeepSeek V4 Flash Free · 7.3s)

_Thinking:_

Good, I now have a solid picture of the datasets. Let me create 5 practice problems of increasing difficulty that test the skills they've learned. I should also fix the KeyError they were stuck on.

The KeyError from 20260705-일요실습1.ipynb:
```python
sub_pay_graph_init_okay=sub_pay_graph2_init=sub_pay[['경인선','경의선','경원선','경부선','경강선']]
```

The error is because they tried to select column names '경인선', '경의선', etc., but those are not column names in `sub_pay` DataFrame. Those are likely values in the '호선명' column (subway line names that include lines like 경인선, 경의선 in addition to 1~9호선). They should filter rows, not columns.

The correct way would be:
```python
sub_pay[sub_pay['호선명'].isin(['경인선','경의선','경원선','경부선','경강선'])]
```

Let me create 5 good practice problems and also explain the error.

**Tool: todowrite**

**Input:**
```json
{
  "todos": [
    {
      "content": "에러 원인 설명 및 해결 코드 제공",
      "status": "in_progress",
      "priority": "high"
    },
    {
      "content": "iris.csv로 문제 1: groupby + 통계",
      "status": "pending",
      "priority": "high"
    },
    {
      "content": "netflix.csv로 문제 2: 조건 필터링 + value_counts",
      "status": "pending",
      "priority": "high"
    },
    {
      "content": "bank.csv로 문제 3: 결측치 처리 + groupby",
      "status": "pending",
      "priority": "high"
    },
    {
      "content": "sales_by_employee.csv로 문제 4: sort + 파생변수 + plot",
      "status": "pending",
      "priority": "high"
    },
    {
      "content": "weather.csv로 문제 5: merge 또는 concat",
      "status": "pending",
      "priority": "medium"
    }
  ]
}
```

**Output:**
```
[
  {
    "content": "에러 원인 설명 및 해결 코드 제공",
    "status": "in_progress",
    "priority": "high"
  },
  {
    "content": "iris.csv로 문제 1: groupby + 통계",
    "status": "pending",
    "priority": "high"
  },
  {
    "content": "netflix.csv로 문제 2: 조건 필터링 + value_counts",
    "status": "pending",
    "priority": "high"
  },
  {
    "content": "bank.csv로 문제 3: 결측치 처리 + groupby",
    "status": "pending",
    "priority": "high"
  },
  {
    "content": "sales_by_employee.csv로 문제 4: sort + 파생변수 + plot",
    "status": "pending",
    "priority": "high"
  },
  {
    "content": "weather.csv로 문제 5: merge 또는 concat",
    "status": "pending",
    "priority": "medium"
  }
]
```

---

## Assistant (Build · DeepSeek V4 Flash Free · 14.5s)

_Thinking:_

Now let me write out the full response with the error fix and all 5 problems.

## 1. 네 에러부터 고쳐줌

```python
# 🔴 틀린 코드 (네가 한거)
sub_pay_graph_init_okay = sub_pay[['경인선','경의선','경원선','경부선','경강선']]
```

```python
# ✅ 맞는 코드 (열 선택 vs 행 필터링 구분!)
sub_pay_graph_init_okay = sub_pay[sub_pay['호선명'].isin(['경인선','경의선','경원선','경부선','경강선'])]
```

**왜 틀렸는지:** `경인선` 등은 **컬럼(열) 이름이 아니라**, `호선명` 컬럼 안에 들어있는 **값(데이터)** 다.  
`df[['col1','col2']]` 는 열을 선택하는 거고,  
`df[df['col'] == 값]` 또는 `df[df['col'].isin([값1,값2])]` 는 행을 필터링하는 거다.

---

## 2. 연습 문제 5개

### 문제 1 — iris (난이도: 하)

```python
import pandas as pd
import matplotlib.pyplot as plt
plt.rc('font', family='Malgun Gothic')

df = pd.read_csv('iris.csv')

# Q1-1: 데이터 구조 파악 (행 수, 열 수, 컬럼명, 데이터 타입)
# 힌트: .shape, .info()

# Q1-2: 종(species)별로 sepal_length의 평균 출력
# 힌트: groupby('species')['sepal_length'].mean()

# Q1-3: 종별 sepal_length, petal_length의 평균을 막대그래프로
# 힌트: groupby('species')[['sepal_length','petal_length']].mean().plot(kind='bar')
```

### 문제 2 — netflix (난이도: 하)

```python
df = pd.read_csv('netflix.csv')

# Q2-1: type(TV Show / Movie)별 개수 세기
# 힌트: value_counts()

# Q2-2: TV Show만 뽑아서 title 출력 (상위 10개)
# 힌트: df[df['type'] == 'TV Show']['title'].head(10)

# Q2-3: 감독(director)별 작품 수 TOP5 출력
# 힌트: df['director'].value_counts().head(5)
```

### 문제 3 — bank (난이도: 중)

```python
df = pd.read_csv('bank.csv')

# Q3-1: balance(통장잔고)가 0 이상인 사람만 필터링해서 평균 나이 구하기
# (age 컬럼은 없지만 duration으로 대체 가능)
# 힌트: df[df['balance'] >= 0]['duration'].mean()

# Q3-2: education(교육수준)별 balance 평균 구해서 내림차순 정렬
# 힌트: df.groupby('education')['balance'].mean().sort_values(ascending=False)

# Q3-3: y(정기예금 가입여부)별 balance 평균을 막대그래프로
```

### 문제 4 — sales_by_employee (난이도: 중)

```python
df = pd.read_csv('sales_by_employee.csv')

# Q4-1: Date를 datetime 타입으로 변환
# 힌트: df['Date'] = pd.to_datetime(df['Date'])

# Q4-2: 'Profit' 컬럼 추가 (Revenue - Expenses)
# 힌트: df['Profit'] = df['Revenue'] - df['Expenses']

# Q4-3: 직원(Name)별 Revenue 합계 TOP3 출력
# 힌트: df.groupby('Name')['Revenue'].sum().sort_values(ascending=False).head(3)

# Q4-4: 직원별 Profit 합계를 막대그래프로
```

### 문제 5 — nba + weather (난이도: 중상)

```python
# Q5-1: nba 데이터에서 Team(팀)별 평균 Salary 구해서
#        내림차순 TOP5 팀을 막대그래프로
df = pd.read_csv('nba.csv')

# Q5-2: 날짜별로 가장 더웠던 날 TOP3
df2 = pd.read_csv('weather.csv')
# 힌트: df2.sort_values(by='temp', ascending=False).head(3)
```

---

**지금 당장 실행해봐라.** 막히면 "어디까지 했는데 여기서 안된다"고 말해라. 

---

