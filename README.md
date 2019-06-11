# COMIC: Towards a Compact Image Captioning Model with Attention

This repo contains **pre-trained model checkpoints** ONLY.
The main repo is 
[here](https://github.com/jiahuei/COMIC-Compact-Image-Captioning-with-Attention).

Released on 05 June 2019.


## Using the checkpoints
Just point `infer.py` to the directory containing the checkpoints. 
Model configurations are loaded from `config.pkl`.

For example:
```bash
python infer.py   \
    --infer_checkpoints_dir mscoco/radix_b256_add_LN_softmax_h8_tie_lstm_cnnFT_run_01
```


## Version
The checkpoints should be compatible with release v1.0 through v1.1.


## Misc
The size of the checkpoints may be larger as they include CNN weights.

## Citation
If you find this repository useful for your research or work, please cite:

```
@article{tan2019comic,
  title={COMIC: Towards A Compact Image Captioning Model with Attention},
  author={Tan, Jia Huei and Chan, Chee Seng and Chuah, Joon Huang},
  journal={IEEE Transactions on Multimedia},
  year={in Press},
  publisher={IEEE}
}
```


## Feedback
Suggestions and opinions (both positive and negative) are greatly welcomed. 
Please contact the authors by sending an email to 
`tan.jia.huei at gmail.com` or `cs.chan at um.edu.my`.


## License and Copyright
The project is open source under BSD-3 license (see the `LICENSE` file).

&#169; 2019 Center of Image and Signal Processing, 
Faculty of Computer Science and Information Technology, University of Malaya.
