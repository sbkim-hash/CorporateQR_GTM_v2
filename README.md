# Corporate QR - GTM Strategy Dashboard

Thailand·Malaysia MSME 법인 결제(QR/카드) 시장 진출 전략 대시보드.

**Live**: [https://sbkim-hash.github.io/CorporateQR/](https://sbkim-hash.github.io/CorporateQR/)

---

## 구조

| 페이지 | 설명 |
|--------|------|
| **Summary** | Where to · Why so · How to 핵심 요약 |
| **Where to** | 국가 선정 (MSME GDP, 침투율) → 산업별 세그먼트 · Use-case |
| **Why so** | 법인카드 침투율 저하 원인 (Banking / Economic Barriers) |
| **How to** | 국가별 벤치마크 (Thailand: K BIZ vs Malaysia: Airwallex·Swipey·CHIP) 및 User journey 비교 |
| **Appendix** | Key players · Current market · License |

---

## Summary

### Where to

Corporate finance service에 대한 MSME의 높은 수요에도 불구하고, 사용률이 저조한 대표적인 국가는 **Thailand, Malaysia**임

- Thailand의 MSME는 179B USD 규모로 GDP의 35%를 차지하나, 법인의 운전자본 중 31%만 은행 계좌를 통해 거래되며 침투율이 낮음
- Malaysia의 MSME는 134B USD 규모로 GDP의 39%를 차지하나, 법인 계좌를 통해 결제되는 비율이 마찬가지로 38%밖에 되지 않음

세그먼트별 규모와 직원의 법인 결제가 발생하는 use-case를 고려했을 때 두 국가에서는 각각 아래 세그먼트를 타겟할 수 있음

**Thailand**
- 물류 (식자재 도매, 건자재 유통) : 하역/하차 인력비용 결제, 원자재 대금 지불, 배송 중 주유 및 긴급 차량 수리비 처리 등
- 서비스 (호텔, F&B 프랜차이즈) : 식재료 결제, 외부 협력업체/프리랜서 용역비 정산

**Malaysia**
- 도소매 (이커머스) : 소모성 자재 구매
- 물류 (물류 대행) : 수출입 관세 및 통관 대행, 물류 차량 통행료/주차비 결제 등
- 서비스 (광고에이전시, F&B 프랜차이즈) : 식재료 결제, 외부 협력업체/프리랜서 용역비 정산 등

### Why so

두 국가는 공통적으로 1) 은행에서 요구하는 높은 담보 및 서류 요건과 2) 수수료 부담으로 법인카드 발급 및 사용률이 낮음

**1)**
- **복잡한 발행 요건:** 법인 카드 발행 시 감사보고서와 은행 거래 내역 등을 증빙해야 하는데, 보고서 체계가 미비한 영세기업은 이로 인해 발급 자체가 낮음
- **까다로운 한도 설정:** 부동산, 예금 담보를 기반으로 한도를 설정할 수 있어, 담보 자산이 없는 온라인 및 영세기업은 한도 설정에 어려움을 겪음

**2)**
- **수수료:** 법인카드 결제 수수료는 Thailand 2~4%, Malaysia 0.6%로 법인 QR 결제 0.25~0.5% 대비 높은 수수료 부담이 존재함
- **정산 지연:** 또한 신용카드 결제 이후 정산은 일반적으로 T+1~3 영업일 소요되어, 법인 비용 관리에 시간적 격차가 존재함

### How to

#### &lt;단계별 진출 전략&gt;

**Thailand — "높은 완성도, 높은 장벽" (Low Priority)**
- Thailand 정부는 2015년부터 'National e-Payment Master Plan'을 세우고, 모든 은행 계좌를 전화번호나 법인 번호(Tax ID)와 연결하는 PromptPay 인프라를 구축함
- 덕분에 은행들이 이 인프라 위에 법인 전용 관리 기능만 얹으면 바로 '법인 QR 서비스'를 제공할 수 있어, 일찍부터 은행 위주의 법인 QR 서비스가 확대되었음
- ⇒ K BIZ(Kasikorn Bank)가 300만 MSME 중 120만을 확보하여 독점적 위치 보유; 신규 진입장벽 존재
- 또한 핀테크가 신규 진출 시 E-Money 라이선스가 필요하고, 이때 자본금 요건이 1억 바트(약 38억 원)로 매우 높음
- 그럼에도 불구하고, 1) 해당 은행 계좌에 법인을 등록하고, 모든 직원들도 해당 은행 계좌를 신설해야 하는 까다로운 발급/사용 조건, 2) 사용 후 까다로운 정산 시스템으로 여전히 MSME들의 사용 편의성을 제고할 부분은 존재

**Malaysia — "열린 기회, 유연한 생태계" (High Priority)**
- CHIP, Airwallex, Swipey 등 핀테크사가 SME 시장을 혁신 중이나, 아직까지 Thailand만큼 QR 인프라가 단일화되어 있지 않고 침투율도 상대적으로 낮아 **법인카드/QR이 혼재**되어 있는 상황
- 이에 현장 현금결제가 많이 필요한 도소매 유통, F&B 프랜차이즈는 CHIP (QR만 제공), 해외 결제가 많은 테크/에이전시는 Swipey (최근까지 카드만 제공), 다국적 기업 대상 Airwallex (카드만 제공)로 이용층이 분리되어 있음
- 신규 핀테크사가 E-Money 라이선스 확보 시, 자본금 요건이 상대적으로 낮고(약 3억~15억 원), 금융 규제 샌드박스와 BaaS(Banking-as-a-Service) 인프라도 발달하여 우회 진출이 용이한 구조
- 이에, **법인카드/QR dual track으로 공격적 진출 시, 광범위한 수요층을 확보할 기회** 존재

> **Step 1: Malaysia 우선 진출**
> - **BaaS 기반 화이트라벨 전략:** 직접 라이선스를 취득하는 대신, Xendit 등 로컬 라이선스 보유사 API를 활용해 가상 계좌 및 결제망을 확보하여 법적 책임을 최소화하고 출시 속도를 극대화함
> - **법인카드/QR 동시 제공:** DuitNow QR, 온라인·해외 결제는 Visa 카드를 단일 플랫폼에서 제공
> - **전략적 파트너십:** 1.8만 개 가맹점을 보유한 StoreHub(POS) 등 현지 플랫폼과 연동하여, 가맹점주 및 직원들을 위한 '전용 경비 관리 모듈'로 빠르게 점유율 확보

> **Step 2: Thailand 시장 틈새 공략**
> - **은행 API 연동 SaaS 모델:** 결제 라이선스를 따지 않고, 은행의 Open Banking API를 활용하여 지출 내역을 시각화하고 회계 프로그램(FlowAccount 등)에 자동 전송해주는 '순수 SaaS' 툴로 접근
> - **고도화된 워크플로우:** 은행 앱이 제공하지 못하는 '다단계 승인 구조' 및 'AI 영수증 자동 처리' 기능을 내세워 프리미엄 중소기업 수요 공략

#### &lt;User journey 차별화&gt;

**1) 결제 승인**
- Thailand — K BIZ는 모든 결제 건에 사장(Authorizer) 수동 승인이 필요하여 병목 발생
- Malaysia — Airwallex·Swipey는 사장 사전 승인 없이 한도 내 자유 결제 가능, CHIP은 pre-approval 시 자유 결제 가능하나 QR 전용으로 온라인/해외 결제 불가
- ⇒ '사전 승인 워크플로우' + 'MCC Filtering'을 QR·카드 모두에 적용하여 결제 전 사장 승인과 업종 제한을 동시 적용

**2) 증빙 수집**
- Thailand — K BIZ E-Slip은 거래 확인용일 뿐 Thailand 국세청(RD) e-Tax Invoice 규격이 아님
- Malaysia — 세 업체 모두 LHDN e-Invoice 규격 미지원, CHIP은 회계 소프트웨어 연동도 미출시
- ⇒ 결제와 동시에 두 국가의 국세청 규격 e-Invoice 실시간 자동 생성 + 회계 소프트웨어 자동 연동

---

## Appendix

### Key Players

| 역할 | Thailand | Malaysia |
|------|----------|----------|
| **인프라** | PromptPay (BOT), BAHTNET | DuitNow (PayNet), PayNet |
| **SaaS/App** | K-BIZ (Kasikorn Bank), Krungthai Business (Krungthai Bank), SCB Business Anywhere (SCB) | CHIP, Swipey, Airwallex |

### Current Market — SaaS/App 매출 및 고객 수 (2024 추정)

| 업체 | 국가 | 매출 (M USD) | 고객 수 (M) |
|------|------|-------------|------------|
| K-BIZ (Kasikorn Bank) | Thailand | 80 | 1.2 |
| Krungthai Business | Thailand | 30 | 0.5 |
| SCB Business Anywhere | Thailand | 25 | 0.3 |
| CHIP | Malaysia | 3 | 0.005 |
| Swipey | Malaysia | 2 | 0.002 |
| Airwallex (MY) | Malaysia | 20 | 0.005 |

### License — 라이선스 요건 비교

#### 직접 라이선스 취득 경로

| 항목 | Thailand | Malaysia |
|------|----------|----------|
| 규제기관 | Bank of Thailand (BOT) / Ministry of Finance | Bank Negara Malaysia (BNM) |
| 근거법 | Payment Systems Act B.E. 2560 (2017) | Financial Services Act 2013 (FSA) |
| E-Money 발행 (QR 결제) | **100M THB (~38억 원)** | **RM 5M (~15억 원)** (대규모) / **RM 100K (~3천만 원)** (소규모) |
| 카드 발행 (법인카드) | **100M THB (~38억 원)** | BNM Payment Cards Framework (2022) 준수 |
| Merchant Acquiring | **50M THB (~19억 원)** | **RM 300K~1M (~1~3.5억 원)** |
| Payment Facilitating | **10M THB (~3.8억 원)** | 별도 라이선스 불필요 (EMI 승인 내 포함) |
| 자본 유지 | 납입자본의 75% 이상 유지 | BNM 정책 문서 기준 최소 자본금 유지 |
| 외국인 지분 | 49% 초과 시 FBL 필요 (BOI 승인 시 100% 가능) | 비은행 EMI의 경우 제한 없음 |
| 이사/법인 요건 | Thai-registered limited company, 최소 1명 Thai 국적 이사 | Malaysia 법인 설립, BNM 적격성 심사 |
| 예상 소요기간 | 약 6~12개월 | 약 3~6개월 (Green Lane 시 단축) |

#### 우회 진출 경로

| 경로 | Thailand | Malaysia |
|------|----------|----------|
| BaaS / 화이트라벨 | 은행 Open Banking API 연동, 결제 라이선스 불필요 | Xendit 등 로컬 라이선스 보유사 API 활용, 자체 라이선스 없이 출시 가능 |
| 규제 샌드박스 | BOT Regulatory Sandbox | BNM Fintech Regulatory Sandbox (2024 개정), Green Lane Fast-Track |
| 순수 SaaS | 결제 미처리 시 결제 라이선스 불필요 | 결제 미처리 시 결제 라이선스 불필요 |

**출처:** BOT Payment Systems Act ([bot.or.th](https://www.bot.or.th/en/our-roles/payment-systems/payment-act-oversight.html)), FOSR Law ([fosrlaw.com](https://fosrlaw.com/2025/payment-processing-licenses-in-thailand-updated-2025-overview/)), Bangkok Global Law ([bgloballaw.com](https://www.bgloballaw.com/2024/06/16/requirements-for-e-payment-license-application/)), LexNova Partners ([lexnovapartners.com](https://lexnovapartners.com/fintech-companies-in-thailand-boi-promotions/)), BNM E-Money Policy ([bnm.gov.my](https://www.bnm.gov.my/)), Rahmat Lim & Partners ([rahmatlim.com](https://www.rahmatlim.com/publication/articles/23493/new-bank-negara-policy-document-updates-e-money-regulatory-framework)), Fintechnews MY ([fintechnews.my](https://fintechnews.my/47925/digital-banking-news-malaysia/bnm-e-money-policy-impact-issuers-consumers/)), Skrine ([skrine.com](https://skrine.com/insights/alerts/march-2024/bank-negara-issues-new-fintech-sandbox-framework)), Mondaq ([mondaq.com](http://www.mondaq.com/financial-services/1113272/minimum-capital-funds-requirement-for-merchant-acquiring-services))

---

## 기술 스택

- 단일 HTML 파일 (vanilla JS + inline CSS)
- 차트: SVG 직접 렌더링
- 호스팅: GitHub Pages

## 배포

`main` 브랜치에 푸시하면 GitHub Pages에 자동 반영됩니다.

```bash
git add -A
git commit -m "commit message"
git push origin main
```
