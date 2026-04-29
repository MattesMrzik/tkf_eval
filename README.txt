# Install
```bash
git clone https://github.com/MattesMrzik/tkf_eval.git
cd tkf_eval/
```
if you want to use https instead of ssh then run 
```bash
git config --global url."https://github.com/".insteadOf git@github.com:
git submodule sync --recursive
```
Then run:
```bash
git submodule update --init --recursive
```

# Update
```bash
git pull --recurse-submodules
# this was not necessary for me: :git submodule update --recursive
```
