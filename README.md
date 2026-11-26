# Quandela Cloud Demo Notebook

**[English](#english) · [한국어](#한국어)**

---

## English

A Jupyter notebook that runs a simple photonic experiment once on Quandela Cloud.
It sends one photon into each input of a single beam splitter and checks the Hong-Ou-Mandel effect.

| File | Language |
|---|---|
| `quandela_cloud_demo_en.ipynb` | English |
| `quandela_cloud_demo_ko.ipynb` | Korean |

Each notebook: enter token → build experiment → run on simulator (`sim:belenos`) → (optional) run on QPU (`qpu:belenos`).

### How to use

1. Click the notebook in the file list above, then click the download icon (**Download raw file**) at the top right to save it.
2. Log in to [Quandela Cloud](https://cloud.quandela.com) and open **Notebook** in the left menu.
3. In the Jupyter view, click the upload icon and upload the saved file.
4. Open the notebook and run the cells from top to bottom (**Shift + Enter**).

See Part V of the **Quandela Cloud User Manual** for screen-by-screen instructions.

### Before you start

- A token issued from **Tokens** on the Cloud site
- Access to the `sim:belenos` platform (check under **Platforms** on the Cloud site)
- To run on the QPU: QPU time and access to `qpu:belenos` (ask your organization's administrator)

### Caution

- The token is entered when you run the notebook and is not saved in the file. Never write your token into a notebook or code you share.
- Running on the QPU consumes your assigned time. `RUN_QPU` is `False` by default; set it to `True` to run on the QPU.

### Reference

- Perceval documentation: https://perceval.quandela.net/docs

---

## 한국어

Quandela Cloud에서 간단한 광자 실험을 한 번 실행해 보는 Jupyter 노트북입니다.
빔 스플리터 1개에 광자 2개를 넣어 Hong-Ou-Mandel 효과를 확인합니다.

| 파일 | 언어 |
|---|---|
| `quandela_cloud_demo_ko.ipynb` | 한국어 |
| `quandela_cloud_demo_en.ipynb` | 영어 |

두 노트북 모두 토큰 입력 → 실험 생성 → 시뮬레이터(`sim:belenos`) 실행 → (선택) QPU(`qpu:belenos`) 실행 순서로 진행합니다.

### 사용 방법

1. 위 파일 목록에서 노트북을 누르고, 오른쪽 위의 다운로드 아이콘(**Download raw file**)을 눌러 저장합니다.
2. [Quandela Cloud](https://cloud.quandela.com)에 로그인해 왼쪽 메뉴의 **Notebook**을 엽니다.
3. Jupyter 화면에서 업로드 아이콘을 눌러 저장한 파일을 올립니다.
4. 노트북을 열고 위에서부터 차례로 실행합니다(**Shift + Enter**).

자세한 화면 안내는 **Quandela Cloud 사용자 매뉴얼** Part V를 참고하십시오.

### 실행 전에 필요한 것

- Cloud 사이트 **Tokens**에서 발급한 토큰
- `sim:belenos` 플랫폼 배정 (Cloud **Platforms**에서 확인)
- QPU에서 실행하려면 QPU 사용 시간과 `qpu:belenos` 플랫폼 배정 (소속 기관 관리자에게 요청)

### 주의

- 토큰은 실행할 때 입력받으며 노트북 파일에 저장되지 않습니다. 토큰을 노트북이나 코드에 직접 적어 공유하지 마십시오.
- QPU 실행은 배정받은 사용 시간을 차감합니다. 노트북의 `RUN_QPU`는 기본값이 `False`이며, `True`로 바꿔야 QPU에서 실행됩니다.

### 참고

- Perceval 문서: https://perceval.quandela.net/docs
