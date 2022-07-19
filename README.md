# Face-Recognition-using-opencv
The face recognition comprises to recognize the human face and it I'll be detected.

import cv2
vs=cv2.VideoCapture(0)
while True:
    _,img=vs.read()
    cv2.imshow("VideoStream",img)
    key=cv2.waitkey(1) & 0XFF
    if key==ord("q"):
        break
vs.release()
cv2.destroyAllWindows()
