# Samuel Ato Kwame Baah

**Business and data analyst in financial services, compliance and fraud
detection. Based in Accra, Ghana.**

Seven years in Ghana's microfinance and regulated financial services sector, four
and a half of them on the PwC Ghana-led receivership that handled 370 of the
institutions closed in the 2017–2019 banking-sector clean-up: claims resolution,
AML/KYC verification, fraud detection, and five branches with 100+ staff
reporting in. I am now building the analytics layer on top of that operational
base, in SQL, Python and Excel. IBM Data Analyst Professional Certificate and a
B.Sc. Business Administration (GPA 3.80) both in progress.

## Flagship work

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22163244.svg)](https://doi.org/10.5281/zenodo.22163244)

**[ghana-banking-collapse](https://github.com/SamuelAtokwamebaah/ghana-banking-collapse)**
is an open dataset of the 418 institutions resolved in the clean-up, compiled
from Bank of Ghana primary sources, with a hand-verified analysis of why the 23
savings and loans companies failed. Related-party lending appears in 17 of the
23, and institutions the regulator had determined to be insolvent kept their
deposit-taking licences for a median of more than two years.

[Read the findings](https://samuelatokwamebaah.github.io/ghana-banking-collapse)

**[microfinance-fraud-detection](https://github.com/SamuelAtokwamebaah/microfinance-fraud-detection)**
asks the next question: how much of a fraud of this kind would detection
actually catch. SQL rules and Python anomaly detection run over a synthetic
24-month loan book of 3,000 borrowers with a repayment-skimming scheme injected
into it, modelled on schemes I found by hand as an operator. Across 20
independently generated portfolios it puts a guilty officer at the top of the
queue every time, and both inside the top three every time. At transaction level
it identifies 29% of the skimmed money. It reports the second number as plainly
as the first.

[Open the case dashboard](https://samuelatokwamebaah.github.io/microfinance-fraud-detection)

**[related-party-lending-network](https://github.com/SamuelAtokwamebaah/related-party-lending-network)**
asks how the insiders behind those failures were connected. The institutions,
their owners, holding companies and connected borrowers are modelled as a graph
built only from what two regulators and one Court of Appeal judgment published.
Every node and every edge carries a quoted passage and a line number, and the
loader refuses to build if a quotation is not verbatim at the line it cites. The
graph falls into 17 disconnected structures rather than one network, and that
negative result is the finding. Two things do cross between institutions, one
entity and one closed funding loop, and neither is visible in either regulator's
notice on its own.

[Open the map](https://samuelatokwamebaah.github.io/related-party-lending-network)

## In development

A journal paper on supervisory timing under Act 930, measuring the interval
between the date the Bank of Ghana itself gives for an institution's insolvency
and the date it revoked the licence, against what the statute requires of that
timing. Currently under peer review. Its repository is published when the
article is, so the code and the argument arrive together.

## Elsewhere

I write *The Multinational Mindset*, a monthly newsletter on global markets and
financial services.

[Portfolio and CV](https://sakb.netlify.app) · [LinkedIn](https://linkedin.com/in/samuelatokwamebaah) · samatohobbs@gmail.com
