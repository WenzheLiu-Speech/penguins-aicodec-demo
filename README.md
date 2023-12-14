# Penguins codec demo
Penguins Codec is an AI general audio codec proposed by Tencent Ethereal Audio Lab, with the support of Tencent AI Lab.

Here are some audio samples for the corresponding papers

Penguins Codec has the following features:
* All kinds of audio signals: including speech, noise and music
* High fidelity: comparable speech quality to Opus 20kbps, and outperforms other AI-Codecs such as Encodec, Lyra v1/2, Sliver and Satin
* Relatively low bitrate: 6~10 kbps for WB and SWB
* Low complexity and storage footprint: real-time inference in the real-life RTC software such as Tencent Meet (3A and other modules are all open) for desktop and advanced mobile phones

News:
* Penguins Codec has been used as the reference model for AVS3 P10 [news](https://mp.weixin.qq.com/s?__biz=MzUyMTMwMDg1NA==&mid=2247502424&idx=1&sn=add537f36a6ef85c91a6f8a1bfa33b08&scene=21#wechat_redirect) in 86-th AVS Conference, 2023
* Penguins Codec has already been experienced at QQ for partial machine types
* Penguins Codec has already been experienced at Tencent Meet (腾讯会议) for partial machine types since 2022.


## Citations ##
If you find this code useful in your research, please cite our work:
```bib
@inproceedings{xiao23c_interspeech,
  author={Wei Xiao, Wenzhe Liu, Meng Wang, Shan Yang, Yupeng Shi, Yuyong Kang, Dan Su, Shidong Shang and Dong Yu},
  title={{Multi-mode Neural Speech Coding Based on Deep Generative Networks}},
  year=2023,
  booktitle={Proc. INTERSPEECH 2023},
  pages={819--823},
  doi={10.21437/Interspeech.2023-1490}
}
```
```bib
@article{liu2023high,
  title={A High Fidelity and Low Complexity Neural Audio Coding},
  author={Liu, Wenzhe and Xiao, Wei and Wang, Meng and Yang, Shan and Shi, Yupeng and Kang, Yuyong and Su, Dan and Shang, Shidong and Yu, Dong},
  journal={arXiv preprint arXiv:2310.10992},
  year={2023}
}
```

