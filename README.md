# COMIC: Towards a Compact Image Captioning Model with Attention

Repo containing **pre-trained model checkpoints**.
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
The checkpoints should be compatible with release v1.0 and v1.0.1.


## Misc
The size of the checkpoints may be larger as they include CNN weights.


## License and Copyright
The project is open source under Apache-2.0 license (see the `LICENSE` file).

&#169; 2019 Center of Image and Signal Processing, 
Faculty of Computer Science and Information Technology, University of Malaya.

