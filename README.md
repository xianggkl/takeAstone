# takeAstone
1. torch.load checkpoint = torch.load(pth_file, map_location=torch.device('cpu')) 会先把模型放在第一个gpu上，所以需要设置location到cpu
2. 
