# Payment Management Tracking & Optimization Dashboard 💳📊

Dashboard built in Microsoft Fabric / Power BI to track and optimize the payment cycle, with automatic alerts and multidimensional filtering — designed so multiple areas get visibility without needing additional SAP licenses.

![Demo](docs/media/demo.gif)

## 🧩 What it solves

- Real-time payment cycle tracking and optimization
- Automatic alerts on orders and execution
- Multidimensional filtering by ERC ID, vendor, and coordination
- Breakdown by organizational area
- Access for multiple users without additional SAP licenses

## 🖥️ Dashboard tabs

| Tab | What it shows |
|---|---|
| **Cover** | Landing page with navigation and summary |
| **Pending Orders** | ![Pending Orders](docs/screenshots/pedidos-pendientes.png) |
| **% Executed by order** | ![% Executed](docs/screenshots/pct-ejecutado.png) |
| **Overdue Delivery** | ![Overdue Delivery](docs/screenshots/entrega-vencida.png) |

## 🎥 Full demo

https://www.linkedin.com/feed/update/urn:li:activity:7492639934512713728/

## 🗂️ What's inside

| Folder / file | Content |
|---|---|
| `docs/screenshots/` | Cover and tab screenshots |
| `docs/media/` | Demo GIF |
| `dax/` | The model's 20 DAX measures, anonymized (generic table/column names, internal branding removed) — see `dax/README.md` |

## 🛠️ Stack

- Microsoft Fabric
- Power BI Desktop / Service
- DAX / Power Query
- *(v2 in development)* Direct SAP integration · language switching · theme switching

## 🔒 Note on the data

Vendors, ERC IDs, order numbers, and table/column names in this repo are fictitious or generic — generated as part of an anonymization process before public release. They do not correspond to real data or the actual structure of any organization.

## 📄 License

MIT — use it, learn from it, adapt it to your case. A mention is appreciated but not required.

---

**Gabriel Concepción** · [LinkedIn](https://www.linkedin.com/in/gabriel-concepci%C3%B3n/)
