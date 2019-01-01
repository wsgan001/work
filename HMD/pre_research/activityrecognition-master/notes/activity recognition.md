###1.什么是行为感知？
行为感知就是利用传感器捕获人体特定行为的信号，根据信号来对人的行为作出判断，并根据行为给出相应措施的一个研究方向。从疾病到日常生活，从心理状态到情绪，都可以由特定的行为反映出来。而特定的行为可以由特定的传感器进行捕捉。因此，进行行为感知是有效的。比如，一个可以完整进行行为感知的应用，可以针对学生群体，除运动、社交和睡眠外，还进行了饮食规律、学习表现、个人情绪、精神压力状况等更全面的健康监测研究，这对人的生活水平的提高是有着积极意义的。
行为感知涉及到机器学习、数据挖掘、信号处理等多个研究领域，属于多学科交叉性研究。基本的行为识别过程是，从传感器中获取行为数据，对这些数据进行预处理，提取有意义的特征，然后用机器学习模型进行分类和预测。
###2.行为感知的类别？
从使用的传感器上来划分，行为识别大致可以分为以下几类：
（1）基于视频图像的行为感知。捕捉人体在运动时的视频和图像，通过对这些资料的分析，进行行为识别。
（2）基于可穿戴传感器的行为感知。这一类是目前最火的研究领域，因为大多数的行为都可以由加速度、陀螺仪等低成本传感器进行捕获。现有的绝大多数智能手机、智能手表、手环等，基本都集成了加速度计。因此，利用这些设备进行行为感知非常方便，结果也很好。
（3）基于环境与物体传感器的行为感知。利用RFID数据、声音数据、环境温度、光照等其他外在的数据进行行为感知，可以识别人体所处的环境等。
###3.行为感知目前存在的挑战
行为感知取得了长足的进步，但是仍然有一些问题需要解决：
（1）空类数据。由于行为感知模型只能识别有限种类的行为，连续采集的用户日常生活的数据流仅包含少量与我们感兴趣的行为对应的数据段和大量的无关数据段（空类数据）。那些与行为对应的数据段类似的空类数据很容易干扰模型的学习过程。
（2）行为的个性化与多样性。不仅不同用户的相同行为具有多样性，同一个用户的某一种行为由于部分因素（压力、疲劳程度、情感状态、环境因素等）的影响，也会表现出多样性。
（3）类别不平衡。 用户长期的日常生活中仅包含频繁的周期性行为（如：睡觉、工作等）、大量的间歇性行为（如：喝水）和极少的偶发性行为（如：跌倒），因此针对用户的日常行为进行建模面临类别不平衡问题。