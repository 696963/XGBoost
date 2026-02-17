# utils/data_loader.py
import torch
from torch.utils.data import Dataset

class MyDataset(Dataset):
    def __len__(self):
        return 1000
    def __getitem__(self, idx):
        return torch.randn(10), torch.tensor(0)
