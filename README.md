# Korean-PLM (Korean Pre-trained Language Model)
   
공개된 한국어 사전학습 모델을 기록합니다. 크게 아래 3개의 모델 계열로 구분했으며, 모델 사이즈는 정확하지 않을 수 있습니다.
  
- Encoder Model (BERT 계열)
- Decoder Model (GPT 계열)
- Encoder-Decoder Model (Seq2seq 계열)
  
  
## Encoder Model (BERT 계열)

| Model Name     | Size           |  Link           |
| :------------: | :------------: |  :------------: |
|   LASSL BERT   |   Small (10M)   |      [link](https://huggingface.co/lassl/bert-ko-small)   |
|   LASSL RoBERTa   |   Small (10M)   |      [link](https://huggingface.co/lassl/roberta-ko-small)   |
|   TUNiB ELECTRA (Ko)   |   Small (10M)   |      [link](https://huggingface.co/tunib/electra-ko-small)   |
|   TUNiB ELECTRA (Ko-En)   |   Small (10M)   |      [link](https://huggingface.co/tunib/electra-ko-en-small)   |
|   KoELECTRA   |   Small (10M)   |      [link](https://huggingface.co/monologg/koelectra-small-v3-discriminator)   |
|  KcELECTRA   |   Small (10M)   |     [link](https://huggingface.co/beomi/kcelectra-v2022-dev)   |
|   Ko-CHAR-ELECTRA  |   Small (10M)   |     [link](https://huggingface.co/monologg/kocharelectra-small-discriminator)   |
|   KE-T5 (Ko-En)   |   Small (60M)   |      [link](https://huggingface.co/KETI-AIR/ke-t5-small)   |
|   KE-T5 (Ko)   |   Small (60M)   |      [link](https://huggingface.co/KETI-AIR/ke-t5-small-ko)   |
|   LMKor T5  |   Small (60M)   |     [link](https://huggingface.co/kykim/t5-kor-small)   |
|   KoBERT   |   Base (110M)   |      [link](https://huggingface.co/skt/kobert-base-v1)   |
|   KorBERT   |   Base (110M)   |     [link](https://aiopen.etri.re.kr/service_dataset.php)   |
|   HanBERT   |   Base (110M)  |     [link](https://github.com/monologg/HanBert-Transformers)   |
| KcBERT    |   Base (110M)   |     [link](https://huggingface.co/beomi/kcbert-base)   |
|   KLUE-Roberta   |   Base (110M)  |     [link](https://huggingface.co/klue/roberta-base)   |
|   KoELECTRA   |   Base (110M)   |     [link](https://huggingface.co/monologg/koelectra-base-v3-discriminator)   |
|   KcELECTRA   |   Base (110M)   |     [link](https://huggingface.co/beomi/KcELECTRA-base)   |
|   TUNiB-ELECTRA (Ko)   |   Base (110M)   |      [link](https://huggingface.co/tunib/electra-ko-base)   |
|   TUNiB-ELECTRA (Ko-En)   |   Base (110M)   |     [link](https://huggingface.co/tunib/electra-ko-en-base)   |
|   LMKor Albert   |   Base (110M)   |      [link](https://huggingface.co/kykim/albert-kor-base)   |
|   LMKor Bert   |   Base (110M)  |    [link](https://huggingface.co/kykim/bert-kor-base)   |
|   LMKor Funnel   |   Base (110M)   |    [link](https://huggingface.co/kykim/funnel-kor-base)   |
|   LMKor ELECTRA   |   Base (110M)   |   [link](https://huggingface.co/kykim/electra-kor-base)   |
|   KalBERT   |   Base (110M)   |     [link](https://github.com/MrBananaHuman/KalBert)   |
|   LASSL BERT   |   Base (110M)   |      [link](https://huggingface.co/lassl/bert-ko-base)   |
|   Distill-KoBERT   |   Base (110M)   |     [link](https://huggingface.co/monologg/kocharelectra-base-discriminator)   |
|   Ko-CHAR-BERT   |   Base (110M)   |     [link](https://github.com/MrBananaHuman/KoreanCharacterBert)   |
|   Ko-CHAR-ELECTRA   |   Base (110M)   |     [link](https://huggingface.co/monologg/kocharelectra-base-discriminator)   |
|   BrainSBERT   |   Base (110M)   |     [link](https://huggingface.co/hyunwoongko/brainsbert-base)   |
| KcT5     |   Base (220M)   |     [link](https://huggingface.co/beomi/KcT5-dev)   |
| KE-T5 (Ko-En)    |   Base (220M)   |     [link](https://huggingface.co/KETI-AIR/ke-t5-base)   |
| KE-T5 (Ko)    |   Base (220M)   |     [link](https://huggingface.co/KETI-AIR/ke-t5-basko)   |
| KcBERT     |   Large (340M)   |     [link](https://huggingface.co/beomi/kcbert-large)   |
|   KLUE-Roberta   |   Large (340M)  |   [link](https://huggingface.co/klue/roberta-large)   |  
| KE-T5 (Ko-En)    |   Large (770M)   |     [link](https://huggingface.co/KETI-AIR/ke-t5-large)   |
| KE-T5 (Ko)    |   Large (770M)   |     [link](https://huggingface.co/KETI-AIR/ke-t5-large-ko)   |
  
## Decoder Model (GPT 계열)
  
| Model Name     | Size           |  Link           |
| :------------: | :------------: |  :------------: |
|   LASSL GPT2   |   Small (20M)   |      [link](https://huggingface.co/lassl/gpt2-ko-small)   |
|   LMKor KoGPT2   |   Base (110M)   |      [link](https://huggingface.co/kykim/gpt3-kor-small_based_on_gpt2)   |
|   SKT KoGPT2   |   Base (110M)   |      [link](https://huggingface.co/skt/kogpt2-base-v2)   |
|   SKT KoGPT2   |   Base (110M)   |      [link](https://huggingface.co/skt/kogpt2-base-v2)   |
|   KakaoBrain KoGPT   |   6B   |      [link](https://huggingface.co/kakaobrain/kogpt)   |
  
## Encoder-Decoder Model (Seq2seq 계열)  
  
| Model Name     | Size           |  Link           |
| :------------: | :------------: |  :------------: |
|   Cosmoquester BART   |   Mini (13M)   |      [link](https://huggingface.co/cosmoquester/bart-ko-mini)   |
|   Cosmoquester BART   |   Small (40M)   |      [link](https://huggingface.co/cosmoquester/bart-ko-small)   |
|   LMKor BERT Shared   |   Base (130M)   |      [link](https://huggingface.co/kykim/bertshared-kor-base)   |
|   SKT KoBART   |   Base (130M)   |      [link](https://huggingface.co/gogamza/kobart-base-v2)   |
|   Cosmoquester BART   |   Base (130M)   |      [link](https://huggingface.co/gogamza/kobart-base-v2)   |
|   Asian BART (Ko)   |   Base (360M)   |      [link](hyunwoongko/asian-bart-ko)   |
|   mBART   |   Large (610M)   |      [link](https://huggingface.co/facebook/mbart-large-50)   |
