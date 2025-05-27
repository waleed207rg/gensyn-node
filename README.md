# gensyn-node
first step after opening vps 

```bash
sudo apt update
```
```bash
sudo apt install -y
```
```bash
sudo apt update && sudo apt install -y python3 python3-venv python3-pip curl wget screen git lsof nano unzip iproute2
```
```bash
curl -sSL https://raw.githubusercontent.com/zunxbt/installation/main/node.sh | bash
```

```bash
screen -S gensyn
```
5. **Run the swarm**
```bash
cd $HOME && rm -rf gensyn-testnet && git clone https://github.com/zunxbt/gensyn-testnet.git && chmod +x gensyn-testnet/gensyn.sh && ./gensyn-testnet/gensyn.sh
-

```

after login now use the trick 
crtl + c
```bash
cd $HOME/rl-swarm/hivemind_exp/configs/mac/
```
```bash
ls
```
grpo-qwen-2.5-0.5b-deepseek-r1.yaml

```bash
RL_SWARM_UNSLOTH=False ./run_rl_swarm.sh
```


 ## 🔄️ Back up `swarm.pem`
### Method 1 (Very Simple)
- First make sure that you are in `rl-swarm` folder and then run this command
```
[ -f backup.sh ] && rm backup.sh; curl -sSL -O https://raw.githubusercontent.com/zunxbt/gensyn-testnet/main/backup.sh && chmod +x backup.sh && ./backup.sh
```













```bash
./run_rl_swarm.sh

after login and running now use the trick 


