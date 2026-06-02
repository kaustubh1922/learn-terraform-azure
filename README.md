1. **Resource Group**: Acts as the logical container holding all interconnected resources.
2. **Virtual Network (VNet)**: Establishes an isolated network boundary, enabling secure communication paths for future subnets, VMs, and data layers.

---

## 🛠️ Project Structure & Component Breakdown

```text
learn-terraform-azure/
├── .git/                 # Git version history tracking
├── .gitignore            # Security shield preventing state & secret leaks
├── main.tf               # Core HCL infrastructure blueprint
└── README.md             # Project documentation & execution guide
│
└── 📁 Resource Group (e.g., "myTFResourceGroup" in West US 2)
│
└── 🌐 Virtual Network (VNet)
