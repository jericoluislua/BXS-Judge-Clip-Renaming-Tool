# BXS-Judge-Clip-Renaming-Tool
This tool helps players/bladers identify which judge clips are theirs without having to play each clip one by one. It was built using the text recognition tool PaddleOCR.

There are two different procedures.

When the name tags are on the side of the player, it splits the frame into two smaller images, isolates the name tags, and rotates the image to help PaddleOCR recognize the letters more accurately.

<img width="1370" height="768" alt="old_clip" src="https://github.com/user-attachments/assets/f159f309-cd85-4473-8bb7-94b8b1d59ac8" />

<img width="2160" height="620" alt="Copy of Img 0044_p2_ocr" src="https://github.com/user-attachments/assets/40b50511-c6e2-4f18-ae3a-5fa2d0b9fbea" />
<img width="2160" height="620" alt="Copy of Img 0044_p1_ocr" src="https://github.com/user-attachments/assets/26e7ad6a-4cf7-4683-a2ae-686c32c70bcf" />

In the newer version, where the name tags are directly in front of the camera, it reads all words and compares them against the name list to find the most accurate match.

<img width="3840" height="486" alt="IMG_0973_ocr" src="https://github.com/user-attachments/assets/640052d7-7d91-4818-97df-78985b77e81d" />
