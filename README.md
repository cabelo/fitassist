![image](https://github.com/cabelo/fitassist/assets/675645/341396d6-7259-4035-969a-0241534a706d)

# fitassist

Given that an instructor cannot supervise all students simultaneously, this system allows the instructor to receive alerts when students do not correctly complete the sequence of physical exercises.
Overview / Usage
By using a skeleton detection algorithm, it is possible to analyze whether exercise movements are being executed correctly. Since an instructor cannot supervise all students simultaneously, this system allows the instructor to receive alerts when students do not correctly complete the sequence of physical exercises. Injuries can occur due to improperly performed motor gestures, where incorrect postures lead to imbalanced loads on the spine and joints, increasing the risk of joint injuries and postural deviations. This can lead to muscular and mental fatigue, often resulting in excessive training, known as overtraining.

## Methodology / Approach
The use of openVINO technology, in synergy with openCV, will be implemented to process the sophisticated algorithm responsible for skeleton detection. Both tools offer a range of functionalities and advantages that make them suitable choices for this complex task. They bring with them a level of efficiency and precision that is essential for the smooth operation of the aforementioned algorithm.

Additionally, the openVPL library, which is part of the widely respected oneAPI package, will be strategically used to transmit videos. The supported formats will be AV1 and H265, which are known for their high efficiency and quality of compression. These videos will then be forwarded to a designated server responsible for processing the inference.

In this way, all these technologies will be used together to ensure a smooth and effective operation, maximizing the precision and speed of the processing of the skeleton detection algorithm, while ensuring an efficient and high-quality video transmission.

## Technologies Used
- openVINO
- openCV
- oneAPI/oneVPL
- SUSE Linux
