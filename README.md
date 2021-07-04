# Install and Run
<details>
<summary>Install</summary>

```bash
$ pip install -r requirements.txt
```
</details>

<details>
<summary>Inference with detect.py</summary>

`detect.py` runs inference on a variety of sources, saving results to `runs/detect`.
```bash
$ python detect.py --source 0  # webcam
                            file.jpg  # image 
                            file.mp4  # video
                            path/  # directory
                            path/*.jpg  # glob
                            'https://youtu.be/NUsoVlDFqZg'  # YouTube video
                            'rtsp://example.com/media.mp4'  # RTSP, RTMP, HTTP stream
```
</details>