# Estrous-Detection-in-Dairy-Cattles-Dataset
---
Data Set for your Project
---
To accurately detect estrus in cattle, a combination of behavioral and physiological parameters is essential. In this research, four primary parameters steps, jumps, voice pitch, and body temperature were used. During the estrus phase, cows show increased physical activity, reflected in a higher number of steps and jumps. Voice pitch often elevates due to restlessness and hormonal changes, while a slight rise in body temperature further indicates the onset of heat. In addition to these indicators, mucus discharge serves as a strong visual sign of estrus; its presence typically confirms that the cow is in full heat, while its absence suggests the opposite. Hormonal analysis also plays a critical role low levels of progesterone and high levels of estrogen are typically observed during estrus, providing a biochemical confirmation of the animal’s fertility status. Together, these behavioral and hormonal cues improve the accuracy of estrus detection, helping farmers optimize breeding decisions and improve herd reproductive performance.
---
## Features of Dataset
- **Steps:**
  
  During estrus, cows exhibit increased physical activity. A noticeable rise in the number of steps taken indicates restlessness, which is a common behavioral change associated with the heat period. Monitoring step count helps in identifying this elevated movement pattern.
  
- **Jumps (Mounting Behavior):**
  
  Cows in estrus often attempt to mount other animals or are more receptive to being mounted. Counting the number of jumps or mounting attempts provides a reliable indicator that the cow may be in heat.
  
- **Voice Pitch:**
  
  Estrus can cause changes in vocal behavior. Cows may vocalize more frequently or at higher pitches due to hormonal shifts and agitation. Monitoring voice pitch allows the system to detect these subtle behavioral changes linked to estrus.
  
- **Body Temperature:**
  
  A slight increase in body temperature is another physiological sign of estrus. This rise is caused by hormonal activity and can be measured using a thermistor sensor, adding valuable insight to the detection process.
  
- **Mucus Discharge:**
  
  The presence of clear, elastic mucus from the vulva is a strong visual indicator of estrus. If mucus is visible, it generally confirms that the cow is in full heat. Its absence may suggest that the cow is not currently in the fertile phase.
  
- **Progesterone Level:**
  
  Hormonal changes are critical in confirming estrus. During heat, progesterone levels drop while estrogen levels rise. These shifts signal that the cow is in a fertile period, making this parameter vital for precise estrus detection and successful artificial insemination planning.

- **Ready for Insemination:**

    The target column Ready for Insemination is used to indicate whether a dairy cow is in the optimal phase of its estrous cycle for artificial insemination. This column acts as the ground truth label for machine learning models, helping determine the cow’s reproductive status based on physiological and behavioral data collected through IoT sensors. A value of 1 in this column means the cow is showing clear signs of estrus—such as increased physical activity (steps and jumps), higher voice pitch, elevated body temperature, or presence of mucus discharge—and is therefore considered to be in heat and ready for insemination. On the other hand, a value of 0 indicates that the cow is not currently in the fertile phase, and insemination at this time would likely not result in conception. This classification is essential for improving breeding efficiency, reducing missed heats, and ensuring timely and successful artificial insemination on dairy farms.
---
## Usage
You are welcome to use this dataset for your own machine learning project, academic research, or agricultural IoT applications. Please consider citing this project if it helps you.
