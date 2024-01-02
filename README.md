<!-- ![](./assets/track-anything-logo.jpg) -->

***Inpaint-Expert*** is a flexible and interactive video object tracking & removing and video inpainting tool. During tracking, users can flexibly change the objects they want to track or correct the region of interest if there are ambiguities. These characteristics enable ***Inpaint-Expert*** to be suitable for: 
- Video object tracking and segmentation with shot changes. 
- Visualized development and data annotation for video object tracking and segmentation.
- Object-centric downstream video tasks, such as video inpainting and editing. 

---

## :computer: Get Started
#### Linux & Windows
```shell
# Clone the repository:
git clone https://github.com/gaomingqi/Track-Anything.git
cd Track-Anything

# Install dependencies: 
pip install -r requirements.txt

# Run the Track-Anything gradio demo.
python app.py --device cuda:0
# python app.py --device cuda:0 --sam_model_type vit_b # for lower memory usage
```

## :clap: Acknowledgements

The project is based on [Track-Anything](https://github.com/gaomingqi/Track-Anything) and [Segment Anything](https://github.com/facebookresearch/segment-anything), [XMem](https://github.com/hkchengrex/XMem), and [E2FGVI](https://github.com/MCG-NKU/E2FGVI). Thanks to the authors for their efforts.
