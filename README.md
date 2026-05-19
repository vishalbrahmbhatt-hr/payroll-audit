# Payroll Audit Tool

A lightweight, browser-based tool that runs structured anomaly checks on payroll data — built to catch the categories of errors that typically slip through manual review cycles.

## What it audits

- **Duplicate records** — same employee paid twice in a cycle, or duplicate UANs/PANs across IDs
- **Band mismatches** — pay falling outside the declared band for an employee's grade/level
- **Statutory deduction errors** — PF, PT, TDS calculations that don't match configured rules
- **Net pay anomalies** — outlier swings between cycles, often a signal of one-off errors

## Why I built it

Most payroll teams run pre-disbursement audits manually — line-by-line, often in Excel, often under time pressure. The tool exists to compress that audit cycle, surface the categories of error worth investigating, and let the payroll analyst focus on judgment rather than discovery.

## Stack

- HTML, CSS, JavaScript (runs entirely in the browser)
- No data leaves the user's machine — all processing is client-side
- Synthetic data only in the repo

## Status

Working prototype. Band ranges and statutory thresholds are configurable before running checks.# payroll-audit
