original repo: https://github.com/michuanhaohao/reid-strong-baseline.git  

## Prepare dataset
* Prepare your dataset at "data/".
* The diretory structure should look like:  
```
data
  sig  
    id_1
      sig_1
      sig_2
      sig_3
      .
      .  
    id_2
      sig_1
      sig_2
      sig_3
      .
      .  
    ...
```
## Train
* Reconfig `train.sh` if needed, see 'config/' for default configs and 'configs/' for some particular configs.  
* Remember to set `OUTPUT_DIR` in `train.sh` to yours.
* Run `sh train.sh`.  
* [Colab](https://colab.research.google.com/drive/1AwA8HliKZfrgXovCHv1oqEYnDM7oQD0v#scrollTo=MTV_o6DEfxdp)

## Augment data
* Add your custom augmentation at "data/transforms/build.py"

* Download font text: 1nhynwV411rnXSw45WqF71rHsUC1z81bu
* Download stamp data: 1Z_xFI5a6mF3yXw5UwdEJokNZDEdheMMF
* Download symbol: 1IqBApbEqY5fuoST7fPPNAfU2EoSvgXcx


## Dowdload pretrained weight

1Ib3etZ16NrkV5bHhp1xTaGpG_ke7A-ty
```wget --load-cookies /tmp/cookies.txt "https://docs.google.com/uc?export=download&confirm=$(wget --quiet --save-cookies /tmp/cookies.txt --keep-session-cookies --no-check-certificate 'https://docs.google.com/uc?export=download&id=1Ib3etZ16NrkV5bHhp1xTaGpG_ke7A-ty' -O- | sed -rn 's/.*confirm=([0-9A-Za-z_]+).*/\1\n/p')&id=1Ib3etZ16NrkV5bHhp1xTaGpG_ke7A-ty" -O  weight.zip && rm -rf /tmp/cookies.txt```
