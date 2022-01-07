# Detect-crown-of-thorns-starfish (still working on)

This project detects starfish by implementing Yolov5, which can be found [here](https://github.com/ultralytics/yolov5). Currently, there is no officially research paper about Yolov5, but in practice, many people used it and it shows a great result. 

Files: 
- Training: detect-crown-of-thorns-starfish-infer.ipynb
- Inference: detect-crown-of-thorns-starfish-infer.ipynb

Result: 
I achived a [F2](https://en.wikipedia.org/wiki/F-score) score of 0.494 on the validation set after 20 epochs. The F2 score weights recall more heavily than the precision, which makes sense because we want to detect as many starfish as we can. 

![image](https://user-images.githubusercontent.com/63311059/148605833-835ace14-33be-4c62-9b10-c0fef7945b33.png)
