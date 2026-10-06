# Awesome Cloud Block Storage 🗄️ ⚡

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Cloud Block Storage Banner" width="100%">
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Cloud-Block-Storage"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Cloud-Block-Storage?style=social" alt="GitHub Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Cloud-Block-Storage/fork"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Cloud-Block-Storage?style=social" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Cloud-Block-Storage/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Cloud-Block-Storage?color=blue" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Top Cloud Block Storage Ecosystem & Software-Defined Storage Solutions 🚀

**Curated List of Commercial Block Storage Platforms & Open-Source Distributed Storage Systems**  
*Focused on High-Performance Block Volumes, Software-Defined Storage (SDS), Kubernetes Persistent Volumes & Self-Hosted SAN/NVMe Storage Clusters*

**Last updated: October 2026** 📅

---

### 📌 Overview & SEO Summary 🔍

Welcome to the ultimate curated directory of **cloud block storage platforms**, **open-source software-defined storage (SDS) systems**, and **Kubernetes-native storage engines**. Whether you are architecting enterprise-grade cloud workloads with commercial hyperscaler block services (such as *Microsoft Azure Managed Disks*, *Amazon EBS*, *Google Cloud Persistent Disk*, *NetApp Cloud Volumes*, and *Pure Storage Cloud Block Store*), or provisioning self-hosted resilient storage clusters with open-source distributed block storage (like *Ceph*, *OpenEBS*, *Longhorn*, *LINSTOR*, and *Curve*), this repository covers market leaders, low-latency NVMe-over-Fabrics engines, and CSI-compliant persistent volume providers.

---

## 📑 Table of Contents 📋

- [📈 Market Overview & Sector Fragmentation](#-market-overview--sector-fragmentation)
- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute)
- [📊 Star History](#-star-history)
- [🤝 Support & Sponsorship](#-support--sponsorship)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)

---

## 📈 Market Overview & Sector Fragmentation 🌐

The global **Cloud Block Storage and Software-Defined Storage (SDS)** market is estimated at **~$65 Billion in 2026** (projected to reach over **$120 Billion by 2030** driven by enterprise cloud migration, AI training dataset caching, and Kubernetes stateful workloads). The sector is **highly concentrated** among hyperscale cloud providers (AWS, Azure, Google Cloud) who capture over 75% of public cloud block volume revenue, while enterprise SAN vendors (Pure Storage, NetApp) and specialized high-performance SDS software providers compete in a moderately fragmented hybrid cloud and enterprise storage market.

---

## 🏢 SaaS / Commercial Platforms 💳

The cloud block storage market features both hyperscaler native volumes and enterprise storage virtual appliances. Sorted by **Company Valuation / Market Capitalization (Descending)**:

| SaaS / Commercial Platform | Company / Owner | Valuation / Market Cap | Standard Edition Starting Price | Free Tier / Free Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Azure Managed Disks](https://azure.microsoft.com/en-us/products/storage/disks/)** 🔷 | Microsoft | ~$3.90 Trillion | **$0.048/GB-month** (Standard SSD); **$0.12/GB-month** (Premium SSD) | **Free 12-month tier**: 64 GB Premium SSD (P6) + 64 GB Standard SSD (E6) | **Azure-native block storage** — **Ultra Disk** delivers sub-millisecond latency for SAP HANA and top-tier databases. **Azure Elastic SAN** brings on-premises SAN capabilities to cloud with millions of IOPS and built-in DR. ⚡ |
| **[Amazon Elastic Block Store (EBS)](https://aws.amazon.com/ebs/)** ☁️ | Amazon | ~$2.0 Trillion | **$0.08/GB-month** (gp3); **$0.125/GB-month** (gp2) | **Free 12-month tier**: 30 GB of EBS storage + 2,000,000 IOs + 1 GB snapshot storage | **AWS-native block storage** — Available in gp3 (general purpose SSD), io2 Block Express (up to 256,000 IOPS), st1/sc1 (throughput/cold HDD). Snapshots for backup. Instance Store for temporary high-performance storage. 📦 |
| **[Google Cloud Persistent Disk](https://cloud.google.com/persistent-disk/)** 🌐 | Google (Alphabet) | ~$2.0 Trillion | **$0.040/GB-month** (Standard HDD); **$0.170/GB-month** (Balanced SSD) | **Free Trial**: $300 in free credits for 90 days across Google Cloud services | **GCP-native block storage** — **Hyperdisk Extreme** delivers **500,000 IOPS and 10 GiB/s throughput**. Persistent Disk for general workloads. Local SSD for temporary high-performance needs. 🚀 |
| **[NetApp Cloud Volumes](https://www.netapp.com/cloud/)** 🔵 | NetApp | ~$20 Billion | **$0.298/GB-month** (Standard performance tier) | **Free Trial**: 30-day free trial on AWS and Azure marketplaces | **ONTAP in the cloud** — **Azure NetApp Files** is the first-party Azure service built on NetApp technology. **Keystone** provides single pay-as-you-go subscription spanning on-premises and cloud, with 99.999% uptime on Extreme and Premium tiers. 💾 |
| **[Pure Storage Cloud Block Store](https://www.purestorage.com/products/cloud-block-store.html)** 🟣 | Pure Storage | ~$15 Billion | **$0.15/GB-month** (estimated base subscription tier) | **Free Trial**: 30-day free trial deployment on AWS and Azure | **Enterprise SAN in the cloud** — Brings Pure's Purity operating system to AWS and Azure for **workload portability** between on-premises and cloud. **Evergreen//One** offers unified subscription across on-prem, hosted, and public cloud. 🏛️ |
| **[Zadara Storage Cloud](https://www.zadara.com/)** ☁️ | Zadara | ~$300 Million (Private) | **$0.10/GB-month** (VPSA Block Storage) | **Free Trial**: 14-day full feature trial with complimentary storage credits | **Storage-as-a-Service (STaaS)** — Enterprise block, file, and object storage with consumption-based pricing. Available on AWS, Azure, GCP, and on-premises. 🔄 |
| **[Lightbits Cloud](https://www.lightbitslabs.com/)** ⚡ | Lightbits Labs | ~$250 Million (Private) | **$0.08/GB-month** (NVMe/TCP provisioned storage) | **Free Trial**: 30-day enterprise proof-of-concept trial | **NVMe/TCP software-defined block storage** — High-performance storage for Kubernetes and cloud-native workloads. Sub-millisecond latency with standard TCP networks. 🏎️ |
| **[Silk Cloud Platform](https://www.silk.us/)** 🕸️ | Silk | ~$200 Million (Private) | **$0.18/GB-month** (Database Virtualization tier) | **Free Trial**: 30-day proof-of-concept deployment on AWS or Azure | **Cloud data platform** — Accelerates databases and applications by presenting cloud storage as local high-performance block devices. Used for SQL Server, Oracle, and SAP workloads. ⚡ |
| **[StorPool](https://storpool.com/)** 📦 | StorPool | ~$100 Million (Private) | **$0.05/GB-month** (Software-Defined Storage licensing base) | **Free Trial**: 30-day software evaluation license for private clusters | **Software-defined block storage** — High-performance storage for public and private clouds. Used by managed service providers for enterprise-grade block storage. 🗄️ |
| **[Blockbridge](https://blockbridge.com/)** 🧱 | Blockbridge | ~$50 Million (Private) | **$0.07/GB-month** (NVMe volume subscription) | **Free Trial**: 30-day evaluation trial for Kubernetes and Docker clusters | **Software-defined block storage for containers** — NVMe/TCP and iSCSI volumes for Kubernetes, Docker, and VMware. Zero-copy snapshots and replication. 🐳 |

---

## 🔓 Open-Source GitHub Projects 🛠️

Curated list of open-source block storage systems, distributed software-defined storage engines, and Kubernetes CSI drivers.

*Sorted by GitHub Stars Count (Descending)* 🌟

- **[Ceph](https://github.com/ceph/ceph)** [![Stars](https://img.shields.io/github/stars/ceph/ceph?style=social&color=white)](https://github.com/ceph/ceph/stargazers)  
  **The most widely deployed open-source distributed storage system**, LGPL-2.1 / GPL-2.0 / BSD-3-Clause licensed. **14,116+ stars**. **Unified object, block, and file storage** from a single cluster built on commodity hardware. **RADOS** (Reliable Autonomic Distributed Object Store) is the foundation. **RBD** (RADOS Block Device) provides block storage for VMs, databases, and Kubernetes via the **Ceph CSI driver**. **Tentacle (v20)** introduced fast erasure coding for block workloads and an **NVMe over TCP gateway** for SAN-style access over Ethernet. **Rook** (CNCF graduated) is the preferred Kubernetes operator. **10-petabyte all-flash cluster sustaining a terabyte per second** demonstrated. 🐙

- **[OpenEBS](https://github.com/openebs/openebs)** [![Stars](https://img.shields.io/github/stars/openebs/openebs?style=social&color=white)](https://github.com/openebs/openebs/stargazers)  
  **Most popular container-native storage platform for Kubernetes**, Apache-2.0 licensed. **8,991+ stars**. **Collection of data engines and operators** creating different types of **local and replicated persistent volumes** for Kubernetes Stateful workloads. **Stable engines**: Mayastor (NVMe over Fabrics), cStor (replicated block), Local PV (Hostpath, Device, ZFS, LVM). **Raw Block Volume support** — provides direct block device access for databases and storage infrastructure software running in Kubernetes. **CSI-compliant** with dynamic provisioning and storage classes. 🎯

- **[Longhorn](https://github.com/longhorn/longhorn)** [![Stars](https://img.shields.io/github/stars/longhorn/longhorn?style=social&color=white)](https://github.com/longhorn/longhorn/stargazers)  
  **Cloud-native distributed block storage for Kubernetes**, Apache-2.0 licensed. **6,400+ stars**. **100% open source, run anywhere** — no open core or proprietary alternatives. **Built-in incremental snapshots and backups** keep volume data safe in or out of the cluster. **Cross-cluster disaster recovery** with defined RPO/RTO. **Native virtual workload storage backend** — built-in virtual disk image management and **volume live-migration** for Harvester and KubeVirt integration. **Microservices architecture** isolates each volume operation to avoid cascading failures. 🐂

- **[Curve](https://github.com/opencurve/curve)** [![Stars](https://img.shields.io/github/stars/opencurve/curve?style=social&color=white)](https://github.com/opencurve/curve/stargazers)  
  **CNCF sandbox distributed storage system**, Apache-2.0 licensed. **2,341+ stars**. **Cloud-native, high-performance, easy to operate** — distributed storage system providing high performance block storage for OpenStack / QEMU and shared file storage for container workloads. 🗂️

- **[MooseFS](https://github.com/moosefs/moosefs)** [![Stars](https://img.shields.io/github/stars/moosefs/moosefs?style=social&color=white)](https://github.com/moosefs/moosefs/stargazers)  
  **Petabyte-scale distributed file system and software-defined storage**, GPL-3.0 licensed. **1,705+ stars**. **Fault-tolerant, highly performing, scalable** network distributed storage system that spreads data over several physical servers presenting as a single volume. 📦

- **[LINSTOR](https://github.com/LINBIT/linstor-server)** [![Stars](https://img.shields.io/github/stars/LINBIT/linstor-server?style=social&color=white)](https://github.com/LINBIT/linstor-server/stargazers)  
  **High-performance software-defined block storage**, GPL-3.0 licensed. **989+ stars**. **Developed by LINBIT** — manages **replicated volumes across a group of machines** with native Kubernetes integration. **DRBD** integration provides **network replication**. **Separate data and control planes** for maximum availability. **Online live migration of back-end storage**. **LVM/ZFS snapshot support**, thin provisioning, RDMA, NVMe over Fabrics. **REST API** for integration. North-bound drivers for CloudStack, Kubernetes, OpenShift, OpenStack, Proxmox VE, and VMware. ⚡

- **[Sheepdog](https://github.com/sheepdog/sheepdog)** [![Stars](https://img.shields.io/github/stars/sheepdog/sheepdog?style=social&color=white)](https://github.com/sheepdog/sheepdog/stargazers)  
  **Distributed storage system for QEMU**, GPL-2.0 licensed. **988+ stars**. **Block-level storage for KVM/QEMU virtual machines** — provides highly available block volume storage that scales out automatically as more nodes are added to the cluster. 🐑

- **[LizardFS](https://github.com/lizardfs/lizardfs)** [![Stars](https://img.shields.io/github/stars/lizardfs/lizardfs?style=social&color=white)](https://github.com/lizardfs/lizardfs/stargazers)  
  **Open-source distributed file system**, GPL-3.0 licensed. **944+ stars**. **MooseFS fork** with additional software-defined storage capabilities, geo-replication, and fault-tolerance across data centers. 🦎

- **[SeaweedFS](https://github.com/seaweedfs/seaweedfs)** [![Stars](https://img.shields.io/github/stars/seaweedfs/seaweedfs?style=social&color=white)](https://github.com/seaweedfs/seaweedfs/stargazers)  
  **Fast distributed storage system**, Apache-2.0 licensed. **22,500+ stars**. Includes **SeaweedFS Block Device (volume management)** and FUSE driver to expose distributed blob chunks as high-speed block devices and persistent volumes. 🌊

- **[Garage](https://github.com/dxflrs/garage)** [![Stars](https://img.shields.io/github/stars/dxflrs/garage?style=social&color=white)](https://github.com/dxflrs/garage/stargazers)  
  **Lightweight distributed object and block storage service**, AGPL-3.0 licensed. **3,800+ stars**. Designed for self-hosting across geo-distributed nodes with minimal system memory footprint. 🚗

- **[DAOS](https://github.com/daos-stack/daos)** [![Stars](https://img.shields.io/github/stars/daos-stack/daos?style=social&color=white)](https://github.com/daos-stack/daos/stargazers)  
  **Exascale-class distributed storage stack**, Apache-2.0 licensed. **763+ stars**. **Intel-led** — designed for **next-generation HPC and AI workloads** with NVMe and PMEM support providing non-volatile memory block abstractions. 🔬

- **[Ceph NVMe-oF Gateway](https://github.com/ceph/ceph-nvmeof)** [![Stars](https://img.shields.io/github/stars/ceph/ceph-nvmeof?style=social&color=white)](https://github.com/ceph/ceph-nvmeof/stargazers)  
  **Service providing Ceph storage over NVMe-oF/TCP protocol**, LGPL-2.1 licensed. **90+ stars**. **Presents block storage to any standard NVMe initiator** — highly available, SAN-style access over ordinary Ethernet with no proprietary hardware. 🔗

- **[Terraform IBM Cluster Storage Module](https://github.com/terraform-ibm-modules/terraform-ibm-cluster-storage)** [![Stars](https://img.shields.io/github/stars/terraform-ibm-modules/terraform-ibm-cluster-storage?style=social&color=white)](https://github.com/terraform-ibm-modules/terraform-ibm-cluster-storage/stargazers)  
  **Terraform module for IBM Cloud cluster storage**, Apache-2.0 licensed. **4+ stars**. **Creates and configures different storage types** like Portworx, object storage, and block storage for IBM Cloud clusters. ☁️

---

## 🛠️ How to Contribute 🤝

Contributions are welcome! Follow these steps to submit new cloud block storage platforms or open-source storage software:

1. 🍴 **Fork** the repository.
2. 📝 **Add/edit** entries in `README.md` maintaining table/list structure and formatting.
3. 🔗 Include project title, official website/GitHub link, exact Stars Count, license, and brief description.
4. 🚀 Submit a **Pull Request** with a descriptive summary of your changes.

---

## 📊 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Cloud-Block-Storage&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Cloud-Block-Storage&type=date&legend=top-left)

---

## 🤝 Support & Sponsorship ☕

If you find this cloud block storage repository useful, please consider supporting the project:

- ⭐ **Star** this repository to increase visibility!
- 🔀 **Fork** and share with fellow storage engineers, SREs, and open-source advocates.
- ☕ **Sponsor & Buy Me a Coffee**: Support ongoing open-source curation via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## ⚠️ Disclaimer ℹ️

- This is a **community-curated** list — not exhaustive and not an official endorsement. ℹ️
- **Ceph is the dominant open-source choice** for software-defined block storage, but **operational complexity is significant** — it requires multiple nodes for quorum and DRBD/RADOS replication, and production deployments benefit from dedicated storage expertise. **Longhorn** and **OpenEBS** are simpler Kubernetes-native alternatives that trade some raw throughput scalability for ease of management. 🛠️
- **Cloud-native block storage costs accumulate from provisioned IOPS**, not just GB-month. AWS io2 volumes charge **$0.0058 per provisioned IOPS** beyond the base tier. **Google Hyperdisk Extreme** delivers 500,000 IOPS but at premium pricing. 💸
- Open-source solutions (Ceph, OpenEBS, Longhorn, LINSTOR) provide self-hosted ownership and transparency, but enterprise-grade SLA guarantees, 24/7 support, and managed infrastructure remain primarily commercial offerings. **Always benchmark IOPS, throughput, and latency for your specific workload** before committing. ⚡

---

<p align="center">
  <b>Made with ❤️ for storage engineers, SREs, and open-source block storage advocates.</b>
</p>
