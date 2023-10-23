# Visualizaiton of Data Samples

## MMBench (EN / CN)

<table class="center">
	<tr>
		<th style="text-align:center;", colspan=2, width="50%"><b>Logic Reasoning:<br>Structuralized Imagetext Understanding</b></th>
		<th style="text-align:center;", colspan=2, width="50%"><b>Finegrained Perception (cross-instance):<br>Action Recognition</b></th>
	</tr>
	<tr>
		<td colspan=2><img src="MMBench/1.jpg" width="100%"></td>
		<td colspan=2><img src="MMBench/21.jpg" width="100%"></td>
	</tr>
	<tr>
		<td colspan=2><p>QUESTION. What is correct Python code to generate the content of the image?<br><br>Options:<br>A. for x in range(6):<br>     print(x)<br>   else:<br>     print("Finally finished!")<br>   <br>B. thisdict = {<br>     "brand": "Ford",<br>     "model": "Mustang",<br>     "year": 1964<br>   }<br>   <br>   print(len(thisdict))<br>C. x = 1<br>   y = 2.8<br>   z = 1j<br>   <br>   print(type(x))<br>   print(type(y))<br>   print(type(z))<br>   <br>D. fruits = ["apple", "banana", "cherry"]<br>   for x in fruits:<br>     print(x)<br><br>ANSWER. D<br></p></td>
		<td colspan=2><p>QUESTION. Which one is the correct caption of this image?<br><br>Options:<br>A. A man rides a surfboard on a large wave.<br>B. a young boy barefoot holding an umbrella touching the horn of a cow<br>C. A giraffe standing by a stall in a field.<br>D. A stop sign that has been vandalized with graffiti.<br><br>ANSWER. B<br></p></td>
	</tr>
	<tr>
		<td colspan=2><p>QUESTION. 能生成这张图片上输出的正确 Python 代码是什么?<br><br>Options:<br>A. for x in range(6):<br>  print(x)<br>else:<br>  print("Finally finished!")<br>B. thisdict = {<br>  "brand": "Ford",<br>  "model": "Mustang",<br>  "year": 1964<br>}<br><br>print(len(thisdict))<br>C. x = 1<br>y = 2.8<br>z = 1j<br><br>print(type(x))<br>print(type(y))<br>print(type(z))<br>D. fruits = ["apple", "banana", "cherry"]<br>for x in fruits:<br>  print(x)<br><br>ANSWER. D<br></p></td>
		<td colspan=2><p>QUESTION. 以下哪个是这张图片的正确标题？<br><br>Options:<br>A. 一个人在巨浪上冲浪。<br>B. 一个年轻男孩赤脚拿着伞触摸牛的角。<br>C. 一只长颈鹿站在田野上的货摊旁边。<br>D. 一个被涂鸦破坏的停车标志。<br><br>ANSWER. B<br></p></td>
	</tr>
	<tr>
		<th style="text-align:center;", colspan=2, width="50%"><b>Coarse Perception:<br>Image Scene</b></th>
		<th style="text-align:center;", colspan=2, width="50%"><b>Finegrained Perception (instance-level):<br>Object Localization</b></th>
	</tr>
	<tr>
		<td colspan=2><img src="MMBench/812.jpg" width="100%"></td>
		<td colspan=2><img src="MMBench/672.jpg" width="100%"></td>
	</tr>
	<tr>
		<td colspan=2><p>QUESTION. Which scene category matches this image the best?<br><br>Options:<br>A. rock_arch<br>B. train_interior<br>C. shopfront<br>D. office_cubicles<br><br>ANSWER. A<br></p></td>
		<td colspan=2><p>QUESTION. How many trucks are in this photo?<br><br>Options:<br>A. six<br>B. five<br>C. seven<br>D. eight<br><br>ANSWER. A<br></p></td>
	</tr>
	<tr>
		<td colspan=2><p>QUESTION. 这张图片最符合哪个场景类别？<br><br>Options:<br>A. 岩石拱门<br>B. 火车内部<br>C. 店面<br>D. 办公室隔间<br><br>ANSWER. A<br></p></td>
		<td colspan=2><p>QUESTION. 这张照片中有多少辆卡车？<br><br>Options:<br>A. 六辆<br>B. 五辆<br>C. 七辆<br>D. 八辆<br><br>ANSWER. A<br></p></td>
	</tr>
	<tr>
		<th style="text-align:center;", colspan=2, width="50%"><b>Coarse Perception:<br>Image Topic</b></th>
		<th style="text-align:center;", colspan=2, width="50%"><b>Attribute Reasoning:<br>Function Reasoning</b></th>
	</tr>
	<tr>
		<td colspan=2><img src="MMBench/2789.jpg" width="100%"></td>
		<td colspan=2><img src="MMBench/2705.jpg" width="100%"></td>
	</tr>
	<tr>
		<td colspan=2><p>QUESTION. Which of the following captions best describes this image?<br><br>Options:<br>A. A giraffe eating tree leaves in the desert<br>B. A chimpanzee being petted on the head<br>C. A horse drinking water by the shore<br>D. A black puppy and a baby in the snow<br><br>ANSWER. C<br></p></td>
		<td colspan=2><p>QUESTION. What's the function of the demonstrated object?<br><br>Options:<br>A. Tracking and organizing dates, days, weeks, months, and years.<br>B. Displaying and indicating the current time.<br>C. Reflecting and providing a reflection of the viewer's appearance.<br>D. Providing a comfortable sleeping and resting place.<br><br>ANSWER. A<br></p></td>
	</tr>
	<tr>
		<td colspan=2><p>QUESTION. 以下哪个标题最能描述这张图片？<br><br>Options:<br>A. 一只长颈鹿在沙漠中吃树叶<br>B. 一只黑猩猩被人拍摸头<br>C. 一匹马在岸边喝水<br>D. 一只黑色小狗和一个婴儿在雪地中<br><br>ANSWER. C<br></p></td>
		<td colspan=2><p>QUESTION. 这个展示的物体的功能是什么？<br><br>Options:<br>A. 追踪和组织日期、星期、月份和年份。<br>B. 显示和指示当前时间。<br>C. 反射并提供观察者外貌的反射。<br>D. 提供一个舒适的睡眠和休息场所。<br><br>ANSWER. A<br></p></td>
	</tr>
	<tr>
		<th style="text-align:center;", colspan=2, width="50%"><b>Logic Reasoning:<br>Future Prediction</b></th>
		<th style="text-align:center;", colspan=2, width="50%"><b>Attribute Reasoning:<br>Identity Reasoning</b></th>
	</tr>
	<tr>
		<td colspan=2><img src="MMBench/2222.jpg" width="100%"></td>
		<td colspan=2><img src="MMBench/2368.jpg" width="100%"></td>
	</tr>
	<tr>
		<td colspan=2><p>QUESTION. Based on this image, please predict what will happen next?<br><br>Options:<br>A. This egg will become cooked<br>B. This egg will fall down<br>C. The egg will be broken<br><br>ANSWER. C<br></p></td>
		<td colspan=2><p>QUESTION. What sport are they athletes of?<br><br>Options:<br>A. weightlifting<br>B. diving<br>C. shooting<br>D. gymnastics<br><br>ANSWER. B<br></p></td>
	</tr>
	<tr>
		<td colspan=2><p>QUESTION. 根据这张图片，请预测接下来会发生什么？<br><br>Options:<br>A. 这个鸡蛋会变熟<br>B. 这个鸡蛋会掉下来<br>C. 鸡蛋会破裂<br><br>ANSWER. C<br></p></td>
		<td colspan=2><p>QUESTION. 他们是哪个运动项目的运动员？<br><br>Options:<br>A. 举重<br>B. 跳水<br>C. 射击<br>D. 体操<br><br>ANSWER. B<br></p></td>
	</tr>
	<tr>
		<th style="text-align:center;", colspan=2, width="50%"><b>Attribute Reasoning:<br>Physical Property Reasoning</b></th>
		<th style="text-align:center;", colspan=2, width="50%"><b>Relation Reasoning:<br>Social Relation</b></th>
	</tr>
	<tr>
		<td colspan=2><img src="MMBench/862.jpg" width="100%"></td>
		<td colspan=2><img src="MMBench/1156.jpg" width="100%"></td>
	</tr>
	<tr>
		<td colspan=2><p>QUESTION. What properties do the metals in the image have?<br><br>Options:<br>A. Silver white color.<br>B. Good conductivity.<br>C. Aromatic liquid.<br>D. Good flowability.<br><br>ANSWER. B<br></p></td>
		<td colspan=2><p>QUESTION. What can be the relationship between the two persons in this image?<br><br>Options:<br>A. Father and daughter<br>B. Mother and son<br>C. Brother and sister<br>D. Husband and wife<br><br>ANSWER. B<br></p></td>
	</tr>
	<tr>
		<td colspan=2><p>QUESTION. 这张图片中的金属具有哪些特性？<br><br>Options:<br>A. 银白色。<br>B. 良好的导电性。<br>C. 芳香液体。<br>D. 良好的流动性。<br><br>ANSWER. B<br></p></td>
		<td colspan=2><p>QUESTION. 这张图片中的两个人之间可能是什么关系？<br><br>Options:<br>A. 父女<br>B. 母子<br>C. 兄妹<br>D. 夫妻<br><br>ANSWER. B<br></p></td>
	</tr>
	<tr>
		<th style="text-align:center;", colspan=2, width="50%"><b>Finegrained Perception (instance-level):<br>Attribute Recognition</b></th>
		<th style="text-align:center;", colspan=2, width="50%"><b>Relation Reasoning:<br>Physical Relation</b></th>
	</tr>
	<tr>
		<td colspan=2><img src="MMBench/2318.jpg" width="100%"></td>
		<td colspan=2><img src="MMBench/2399.jpg" width="100%"></td>
	</tr>
	<tr>
		<td colspan=2><p>QUESTION. What is the approximate shape of this umbrella?<br><br>Options:<br>A. Circle<br>B. Octagon<br>C. Triangle<br>D. Rectangle<br><br>ANSWER. B<br></p></td>
		<td colspan=2><p>QUESTION. Who is closer to the football in the image, the player in the black jersey or the player in the green jersey?<br><br>Options:<br>A. The player in the black jersey.<br>B. The player in the green jersey.<br>C. They are equally close.<br>D. It cannot be determined.<br><br>ANSWER. B<br></p></td>
	</tr>
	<tr>
		<td colspan=2><p>QUESTION. 这把雨伞的大致形状是什么？<br><br>Options:<br>A. 圆形<br>B. 八边形<br>C. 三角形<br>D. 矩形<br><br>ANSWER. B<br></p></td>
		<td colspan=2><p>QUESTION. 在图片中，穿黑色球衣的球员和穿绿色球衣的球员谁离足球更近？<br><br>Options:<br>A. 穿黑色球衣的球员。<br>B. 穿绿色球衣的球员。<br>C. 他们离足球的距离相等。<br>D. 无法确定。<br><br>ANSWER. B<br></p></td>
	</tr>
	<tr>
		<th style="text-align:center;", colspan=2, width="50%"><b>Relation Reasoning:<br>Nature Relation</b></th>
		<th style="text-align:center;", colspan=2, width="50%"><b>Finegrained Perception (cross-instance):<br>Attribute Comparison</b></th>
	</tr>
	<tr>
		<td colspan=2><img src="MMBench/2967.jpg" width="100%"></td>
		<td colspan=2><img src="MMBench/318.jpg" width="100%"></td>
	</tr>
	<tr>
		<td colspan=2><p>QUESTION. In nature, what's the relationship between these two creatures?<br><br>Options:<br>A. Predatory relationships<br>B. Competitive relationships<br>C. Parasitic relationships<br>D. Mutualistic relationship<br><br>ANSWER. A<br></p></td>
		<td colspan=2><p>QUESTION. Which solution has a higher concentration of green particles?<br>HINT. The diagram below is a model of two solutions. Each green ball represents one particle of solute.<br><br>Options:<br>A. neither; their concentrations are the same<br>B. Solution B<br>C. Solution A<br><br>ANSWER. B<br></p></td>
	</tr>
	<tr>
		<td colspan=2><p>QUESTION. 在自然界中，这两种生物之间的关系是什么？<br><br>Options:<br>A. 捕食关系<br>B. 竞争关系<br>C. 寄生关系<br>D. 互利共生关系<br><br>ANSWER. A<br></p></td>
		<td colspan=2><p>QUESTION. 哪个溶液中绿色颗粒的浓度更高？<br>HINT. 下面的图表是两种溶液的模型。每个绿色的球代表一颗溶质粒子。<br><br>Options:<br>A. 都不是；它们的浓度相同<br>B. 溶液 B<br>C. 溶液 A<br><br>ANSWER. B<br></p></td>
	</tr>
	<tr>
		<th style="text-align:center;", colspan=2, width="50%"><b>Finegrained Perception (cross-instance):<br>Spatial Relationship</b></th>
		<th style="text-align:center;", colspan=2, width="50%"><b>Finegrained Perception (instance-level):<br>OCR</b></th>
	</tr>
	<tr>
		<td colspan=2><img src="MMBench/2870.jpg" width="100%"></td>
		<td colspan=2><img src="MMBench/1745.jpg" width="100%"></td>
	</tr>
	<tr>
		<td colspan=2><p>QUESTION. What direction is Yemen in Saudi Arabia?<br><br>Options:<br>A. east<br>B. west<br>C. north<br>D. south<br><br>ANSWER. D<br></p></td>
		<td colspan=2><p>QUESTION. What does this picture want to express?<br><br>Options:<br>A. We are expected to care for green plants.<br>B. We are expected to care for the earth.<br>C. We are expected to stay positive.<br>D. We are expected to work hard.<br><br>ANSWER. B<br></p></td>
	</tr>
	<tr>
		<td colspan=2><p>QUESTION. 也门相对于沙特阿拉伯的方向是？<br><br>Options:<br>A. 东<br>B. 西<br>C. 北<br>D. 南<br><br>ANSWER. D<br></p></td>
		<td colspan=2><p>QUESTION. 这张图片想要表达什么？<br><br>Options:<br>A. 我们应该关心绿色植物。<br>B. 我们应该关心地球。<br>C. 我们应该保持积极。<br>D. 我们应该努力工作。<br><br>ANSWER. B<br></p></td>
	</tr>
	<tr>
		<th style="text-align:center;", colspan=2, width="50%"><b>Finegrained Perception (instance-level):<br>Celebrity Recognition</b></th>
		<th style="text-align:center;", colspan=2, width="50%"><b>Coarse Perception:<br>Image Style</b></th>
	</tr>
	<tr>
		<td colspan=2><img src="MMBench/718.jpg" width="100%"></td>
		<td colspan=2><img src="MMBench/503.jpg" width="100%"></td>
	</tr>
	<tr>
		<td colspan=2><p>QUESTION. Who is the person in this image?<br><br>Options:<br>A. Jackie Chan<br>B. Jing Wu<br>C. Donald Trump<br>D. Steve Jobs<br><br>ANSWER. D<br></p></td>
		<td colspan=2><p>QUESTION. Which can be the associated text with this image posted on twitter<br><br>Options:<br>A. I painted a picture of sushi. It's a colorful and tasty scene.<br>B. look at this cute toy sushi set 🥹<br>C. St. Louis Sushi (ham wrapped around cream cheese and a pickle)<br>D. Perfect Sushi Cake with Fresh Salmon and Avocado A sushi cake is a unique twist on traditional sushi that is perfect for special occasions or a fun meal with friends and family. #SushiCake #salmonavocado #avocado #avocadotoast #cake #recipe #dinner #food #FoodieBeauty<br><br>ANSWER. A<br></p></td>
	</tr>
	<tr>
		<td colspan=2><p>QUESTION. 这张图片中的人是谁？<br><br>Options:<br>A. 成龙<br>B. 吴京<br>C. 唐纳德·特朗普<br>D. 史蒂夫·乔布斯<br><br>ANSWER. D<br></p></td>
		<td colspan=2><p>QUESTION. 与这张推特上图片配套的推文是什么？<br><br>Options:<br>A. 我画了一幅寿司的画。这是一个色彩丰富且美味的场景。<br>B. 看这个可爱的玩具寿司套装 🥹<br>C. 圣路易斯寿司（火腿包裹着奶油奶酪和腌黄瓜）<br>D. 完美的寿司蛋糕，配有新鲜三文鱼和鳄梨。寿司蛋糕是传统寿司的独特变化，非常适合特殊场合或与朋友和家人共进的有趣餐点。#SushiCake #salmonavocado #avocado #avocadotoast #cake #recipe #dinner #food #FoodieBeauty<br><br>ANSWER. A<br></p></td>
	</tr>
	<tr>
		<th style="text-align:center;", colspan=2, width="50%"><b>Coarse Perception:<br>Image Emotion</b></th>
		<th style="text-align:center;", colspan=2, width="50%"><b>Coarse Perception:<br>Image Quality</b></th>
	</tr>
	<tr>
		<td colspan=2><img src="MMBench/544.jpg" width="100%"></td>
		<td colspan=2><img src="MMBench/768.jpg" width="100%"></td>
	</tr>
	<tr>
		<td colspan=2><p>QUESTION. Identify the emotion expressed in this image.<br><br>Options:<br>A. happiness<br>B. sadness<br>C. anger<br>D. love<br><br>ANSWER. A<br></p></td>
		<td colspan=2><p>QUESTION. Which image is the brightest one?<br><br>Options:<br>A. upper left<br>B. upper right<br>C. down left<br>D. down right<br><br>ANSWER. C<br></p></td>
	</tr>
	<tr>
		<td colspan=2><p>QUESTION. 识别这张图片中表达的情感是什么？<br><br>Options:<br>A. 快乐<br>B. 悲伤<br>C. 愤怒<br>D. 爱<br><br>ANSWER. A<br></p></td>
		<td colspan=2><p>QUESTION. 哪张图片是最亮的？<br><br>Options:<br>A. 左上方<br>B. 右上方<br>C. 左下方<br>D. 右下方<br><br>ANSWER. C<br></p></td>
	</tr>
</table>