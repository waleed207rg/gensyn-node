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
```
```bash
screen -S gensyn
```
5. **Run the swarm**
```bash
cd $HOME && rm -rf gensyn-testnet && git clone https://github.com/zunxbt/gensyn-testnet.git && chmod +x gensyn-testnet/gensyn.sh && ./gensyn-testnet/gensyn.sh
- if comes login problem than
```
if any login problem out this commands
 
```bash
cd rl-swarm
```
```bash
nano modal-login/app/page.tsx
```
```bash
useEffect(() => {
  if (!user && !signerStatus.isInitializing) {
    openAuthModal(); 
  }
}, [user, signerStatus.isInitializing]);

login problem will be solved 

now **Run the swarm**
```
```bash
./run_rl_swarm.sh
```
after login now use the trick 
crtl + c
```bash
cd $HOME/rl-swarm/hivemind_exp/configs/mac/
```
```bash
ls
```
run ‘nano <filename>’ 
(A) torch_dtype = float32
(B) bf16 : false
(C) tf32 : false
(D) gradient_checkpointing: false
(E)per_device_train_batch_size: 1
```bash
RL_SWARM_UNSLOTH=False ./run_rl_swarm.sh
```

 ## 🔄️ Back up `swarm.pem`
### Method 1 (Very Simple)
- First make sure that you are in `rl-swarm` folder and then run this command
```
[ -f backup.sh ] && rm backup.sh; curl -sSL -O https://raw.githubusercontent.com/zunxbt/gensyn-testnet/main/backup.sh && chmod +x backup.sh && ./backup.sh
```
- It will show something like this in your terminal














```bash
./run_rl_swarm.sh

after login and running now use the trick 


