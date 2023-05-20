
# 참고사항

detect_bubble.py 13,14 줄

yolov5 처리
model = torch.hub.load('ultralytics/yolov5', 'custom', path='./runs/train/bubble_exp2/weights/best.pt')

부분에서

path='./runs/train/bubble_exp2/weights/best.pt' << 올려놓은 best.pt 파일의 경로를 넣어주면 됩니다.
