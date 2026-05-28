# AI-Cup-2026 code

### 執行方式
- baseline_code.py
```shell
python .\baseline_code.py --epochs 10
```
- baseline_modify.py
```shell
python .\baseline_modify.py --epochs 30 --emb 32 --layers 2 --out "output/baseline_modify_2.csv"
```

### 檔案結構
```
CODE
├── baseline_code.py
├── baseline_modify.py
├── dataset
│   ├── Reference_Only_Old_Test_Data
│   │   ├── README.txt
│   │   └── test.csv
│   ├── sample_submission.csv
│   ├── test_new.csv
│   └── train.csv
└── output
    ├── baseline_modify.csv
    └── submission_lstm_baseline.csv
```
