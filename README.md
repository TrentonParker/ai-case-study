# AI Case Study






## Overview and Origin

* *Name of Project*

[**MinD-Vis**](https://mind-vis.github.io/) (Sparse **M**asked Bra**in** Modeling with **D**ouble-Conditioned Diffusion Model for **Vis**ion Decoding)

* *When was the project incorporated?*

**MinD-Vis was first launched in early November 2022.**

* *Who are the founders of the project?*

The founders of the project are **Zijiao Chen, Wan Lin Yue, and Juan Helen Zhou** of the National University of Singapore; **Jiaxin Qing** of the Chinese University of Hong Kong Department of Information Engineering; and **Tiange Xiang** of the Stanford University Vision and Learning Lab.

* *How did the idea for the project come about?*

**The idea for the project was not quite original, as other researchers have worked on the same thing. However, the project in general aims to deepen the understanding of the human visual system.**

* *How is the project funded? How much funding has it receieved?*

**The project is funded by the respective Universities each founder originates from. There are no specific metrics as to the amount of funding going into MinD-Vis.**

## Business Activities

* *What specific problem is the project trying to solve?*

**MinD-Vis takes fMRI scans of the brain when a patient is given a visual stimulus and decodes and reconstructs the visual stimulus based on the fMRI pattern.** 
> **Decoding visual stimuli from brain recordings aims to deepen our understanding of the human visual system and build a solid foundation for bridging human and computer
vision through the Brain-Computer Interface.**

![alt text](image.png)

* *Who is the project's intended customer? Is there any information about the market size of this set of customers?*

**This project is just that, a project, at this point in time. However, this technology offers major implications to the medical field such as enhanced communication with non-verbal patients, improved non-invasive monitoring of the brain, and other advancements regarding neuroscience research.**

* *What solution does this project offer that their competitors do not or cannot offer?*

> **MinD-Vis offers a state-of-the-art 100-way top-1 classification accuracy on [GOD dataset](https://paperswithcode.com/dataset/god): 23.9%, outperforming the previous best by 66%.**

![alt text](image-2.png)

* *Which technologies are they currently using, and how are they implemented?* 

**MinD-Vis uses Sparse-Coded Masked Brain Modeling (SC-MBM), which is innovative and original to MinD-Vis, as an effective brain feature learner for vision decoding. Also, augmenting the [latent diffusion model](https://medium.com/@aguimarneto/what-is-latent-diffusion-in-ai-43aa1ad4f71e) with double conditioning (DC-LDM) allows MinD-Vis to enforce stronger decoding consistencies while allowing variance under the same semantics.**
>  **Integrating the representation ability of SC-MBM with the generation ability of DC-LDM, MinD-Vis generates more plausible images with better preserved semantic information compared with previous methods.**

![alt text](image-3.png)

## Landscape

* *What field is the project in?*

**This project is in the medicine field.**

* *What have been the major trends and innovations of this field over the last 5 - 10 years?*

**Some [major trends in the medicine field regarding AI](https://www.lapu.edu/ai-health-care-industry/) in the recent past have included AI algorithims analyzing medical imaging data to better diagnose patients, speech recognition technologies to help doctors dictate and better document information on patients, and new drug discoveries.**

* *What are the other major projects in this field?*

**A couple of other researchers, such as [Furkan Ozcelik](https://www.nature.com/articles/s41598-023-42891-8), [Guy Gaziv](https://www.sciencedirect.com/science/article/pii/S105381192200249X), and [Roman Beliy](https://www.sciencedirect.com/science/article/pii/S105381192200249X) are some other leaders in the field. ('Figure 5' above compares MinD-Vis to their work)**

* *How is your project performing relative to competitors in the same field?*

> **MinD-Vis has State-of-the-art 100-way top-1 classification accuracy on GOD dataset: 23.9%, outperforming the previous best by 66%, and State-of-the-art generation quality [(FID)](https://en.wikipedia.org/wiki/Fr%C3%A9chet_inception_distance) on GOD dataset: 1.67, outperforming the previous best by 41%.**

## Recommendations

* *If you were to advise the company, what products or services would you suggest they offer?*

**This would definitely be something I would try and sell to the medical field, to medical facilities that are involved in the neurosciences. You could offer MinD-Vis as a way of gaining a better understanding of how the brain operates when processing visual stimiuli. Another idea I have, which may be a bit far out, is once the technology is super refined and accurate, you could possibly reverse engineer it as a way of allowing blind people to see, with some sort of camera that has the technology to shoot the specific patterns of visual stimuli to the brain, allowing the patient to visualize in their mind what the camera is seeing.**

* *Why do you think that offering this product or service would benefit the company?* 

**It would be a way of monetizing the project's technology to medical companies.**

* *What technologies would this additional product or service utilize?*













