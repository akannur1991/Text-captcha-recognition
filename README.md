# Text-captcha-recognition
This program is CNN based and recognizes the text from captcha images

Example to run the files:
python classify.py --model-name testaudio1.h5 --captcha-dir img2 --output audiotest.txt --symbols symbols1.txt
python evaluator.py --captcha-length 5  --predicted-output evaluate2.txt


python train_grayscale1.py --width 128 --height 64 --length 8 --symbols symbols1.txt --batch-size 1 --epochs 1 --output-model testaudio1.h5 --train-dataset img0 --validate-dataset img1

python classify.py --model-name test1.h5 --captcha-dir example_captchas --output stuff1.txt --symbols symbols.txt

python classify.py --model-name test8 --captcha-dir 19300875textcaptchas --output stuff3.txt --symbols symbols.txt


python generate.py --count 200 --output-dir train3

