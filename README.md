# Consumer Complaint Trends and Response Analysis

## Project overview

This Week 4 data analytics project examines 62,516 consumer complaints about Bank of America recorded by the Consumer Financial Protection Bureau (CFPB) from May 1, 2017 through August 28, 2023. The analysis explores complaint trends, financial products and reported issues, company response classifications, timely-response indicators, and CFPB forwarding intervals.

## Data and tools

The analysis uses `Consumer_Complaints.xlsx` and the accompanying `ConsumerComplaints_DataDictionary.xlsx`. The source workbook was preserved. Microsoft Excel was used for data inspection, validation, calculations, derived fields, and pivot-table analysis. Power BI Desktop was used to build the interactive four-page dashboard.

The analysis includes Year, Month, Quarter, and Forwarding interval fields. Complaint ID was unique in the supplied records. The analysis retained missing sub-issue and public-response values and excluded blank timely-response values from the valid Yes/No percentage.

## Dashboard

1. **Executive Complaint Overview** — total complaints, monthly trend, product distribution, timely-response percentage, average forwarding interval, and Year/Product filters.
2. **Product and Issue Analysis** — complaint counts by financial product and sub-product, most frequently reported issues, and a product-versus-issue matrix.
3. **Company Response Analysis** — company response categories, public response categories, timely Yes/No distribution, and in-progress complaints.
4. **Complaint Timeline Analysis** — annual and monthly trends, forwarding-interval distribution, average interval by product, and the longest observed interval.

## Key results

- Checking or savings accounts had the highest product volume: 24,814 complaints (39.69% of all records).
- Managing an account was the leading issue overall, with 15,109 complaints.
- Closed with explanation was the most frequently recorded company response to consumers: 41,044 complaints (65.7%).
- Among 61,022 valid Yes/No timely-response records, 58,619 were marked Yes (96.1%). The 1,494 blank values were associated with complaints marked In progress and were not classified as No.
- Average forwarding interval was 1.22 days, median was zero days, and the maximum observed interval was 275 days.

## Interpretation

A complaint is an issue reported by a consumer; it does not by itself establish misconduct or prove a regulatory violation. `Date submitted` is when the CFPB received a complaint. `Date received` is when the CFPB sent it to the company. Their difference is the CFPB forwarding interval, not company response or resolution time. The 2017 and 2023 periods are partial years. Blank public-response values indicate that no category was recorded; they are distinct from named public-response categories.

## Supporting documentation

The accompanying `Consumer_Complaint_Project_Documentation.docx` presents the data-quality results, KPI definitions and calculations, evidence-based findings, recommendations, and limitations.
