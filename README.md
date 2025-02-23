# Auto Send EVM

## Deskripsi
Script ini otomatis mengirim token native pada jaringan EVM. Private key diambil dari pvkeys.txt, sedangkan alamat tujuan dari address.txt. Gas fee dihitung otomatis, dan transaksi akan diulang jika gagal.


## Requirements
- Python 3
- `web3.py`
- `colorama`
- `pyfiglet`

## Installation
   ```sh
   git clone https://github.com/Odienurman/auto-send-evm.git
   cd auto-send-evm
```

```sh
pip install -r requirements.txt
```
or
```sh
pip install pyfiglet
```
```sh
pip install web3==6.20.1
```
```sh
pip install colorama
```
## Usage
   ```sh
   python bot.py
   ```
4. Enter the RPC URL, number of transactions per wallet, and amount to send.
5. The script will process transactions automatically.

## Notes
- Pastikan dompet Anda memiliki saldo yang cukup
- Gunakan penyedia RPC yang andal untuk transaksi yang stabil

