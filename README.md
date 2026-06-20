# Professional Invoice & GST Calculator

A lightweight, high-performance, single-page client-side web application designed to compute real-time line-item billing totals and automated Goods and Services Tax (GST) allocations. Built strictly according to the technical requirements and layout constraints specified by Digital Heroes.

## 🚀 Live Deployment
* **Production URL:** [https://vercel.app](https://vercel.app)
* **Alternative Mirror:** [https://vercel.app](https://vercel.app)

## 📊 Core Calculation Engine Matrix

The sandboxed JavaScript execution environment handles currency data computation dynamically using the following financial equations:

1. **Tax-Exclusive Base Subtotal Amount:**
   $$\text{Base Subtotal} = \sum (\text{Item Rate} \times \text{Item Quantity})$$

2. **Isolated Line-Item GST Component Value:**
   $$\text{GST Component Liability} = \text{Base Subtotal} \times \left(\frac{\text{GST Rate Percentage}}{100}\right)$$

3. **Cumulative Gross Payable Amount:**
   $$\text{Total Invoice Gross} = \text{Base Subtotal} + \text{Aggregated GST Liabilities}$$

## 💻 Tech Stack & Architecture
* **Markup Context:** Semantic HTML5 Engine
* **Styling Framework:** Tailwind CSS CDN (v4 Lifecycle Environment)
* **Design Systems:** Inter Typography Interface via Google Fonts API
* **Engine Environment:** Vanilla ECMAScript client-side reactive state engine (Zero external data-layer dependencies for complete privacy compliance)
* **Deployment Pipe:** Vercel Automated Edge Network

## 👤 Developer Profile
* **Developer Name:** Lakshmi Chaitanya K.
* **Project Designation:** Custom Software Developer Assessment Task
* **Target Interface:** Digital Heroes Workspace Co.
