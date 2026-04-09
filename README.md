# gt4o4 · Personal R&D Lab

> High-performance **3D Computer Vision** · **Foundational AI** · **Linux Systems & Drivers** · **Advanced Networking**

A personal research and engineering lab operated by [Wenri](https://github.com/Wenri) ([@s2.hk](https://s2.hk)).  
Explores the intersection of cutting-edge 3D reconstruction, large-scale vision models, bare-metal Linux internals, and high-throughput network infrastructure.

---

## 🔬 3D Computer Vision · Gaussian Splatting · NeRFs

Real-time 3D reconstruction and novel-view synthesis — from classical NeRF pipelines to state-of-the-art 3D Gaussian Splatting variants.

| Repository | Description |
|---|---|
| [3dgs](https://github.com/gt4o4/3dgs) | 3D Gaussian Splatting for real-time radiance field rendering |
| [gaussian-opacity-fields](https://github.com/gt4o4/gaussian-opacity-fields) | Efficient high-quality compact Gaussian Splatting |
| [Geometry-Grounded-Gaussian-Splatting](https://github.com/gt4o4/Geometry-Grounded-Gaussian-Splatting) | Geometry-grounded 3DGS for precise surface reconstruction |
| [PGSR](https://github.com/gt4o4/PGSR) | Planar-based Gaussian Splatting for efficient radiance field rendering |
| [radfoam](https://github.com/gt4o4/radfoam) | Radiance field foam — topology-aware Gaussian representations |
| [SIBR_viewers](https://github.com/gt4o4/SIBR_viewers) | Image-based rendering viewer framework for 3DGS |
| [diffusionerf](https://github.com/gt4o4/diffusionerf) | Diffusion-regularized NeRF for few-shot 3D synthesis |
| [ngp_pl](https://github.com/gt4o4/ngp_pl) | Instant-NGP reimplemented in PyTorch Lightning |
| [dust3r](https://github.com/gt4o4/dust3r) | DUSt3R: Geometric 3D Vision Made Easy |
| [mast3r](https://github.com/gt4o4/mast3r) | Matching And Stereo 3D Reconstruction |
| [croco](https://github.com/gt4o4/croco) | CroCo: Self-supervised pre-training for 3D vision tasks |
| [nvdiffrast](https://github.com/gt4o4/nvdiffrast) | Modular primitives for high-performance differentiable rendering |

---

## 🤖 Foundational AI Models · Computer Vision

Large-scale segmentation, open-vocabulary understanding, point-cloud learning, and multi-modal vision models.

| Repository | Description |
|---|---|
| [vllm](https://github.com/gt4o4/vllm) | High-throughput LLM inference and serving engine |
| [segment-anything](https://github.com/gt4o4/segment-anything) | Segment Anything Model (SAM) by Meta AI |
| [segment-anything-2](https://github.com/gt4o4/segment-anything-2) | SAM 2: Segment Anything in Images and Videos |
| [Depth-Anything-V2](https://github.com/gt4o4/Depth-Anything-V2) | Foundation model for monocular depth estimation |
| [Mask2Former](https://github.com/gt4o4/Mask2Former) | Masked-attention mask transformer for universal segmentation |
| [SegFormer](https://github.com/gt4o4/SegFormer) | Simple and efficient semantic segmentation with Transformers |
| [ODISE](https://github.com/gt4o4/ODISE) | Open-vocabulary panoptic segmentation with diffusion models |
| [clip_dinoiser](https://github.com/gt4o4/clip_dinoiser) | CLIP + DINO feature denoising for open-vocab segmentation |
| [GeoAware-SC](https://github.com/gt4o4/GeoAware-SC) | Geometry-aware semantic correspondence |
| [dift](https://github.com/gt4o4/dift) | Diffusion features for zero-shot 6DoF object pose estimation |
| [mmsegmentation](https://github.com/gt4o4/mmsegmentation) | OpenMMLab semantic segmentation toolbox |
| [mmcv](https://github.com/gt4o4/mmcv) | OpenMMLab foundational computer vision library |
| [pytorch3d](https://github.com/gt4o4/pytorch3d) | PyTorch3D: 3D deep learning utilities by Facebook Research |
| [Pointnet2_PyTorch](https://github.com/gt4o4/Pointnet2_PyTorch) | PointNet++ implementation in PyTorch |
| [pyGDel3D](https://github.com/gt4o4/pyGDel3D) | Python bindings for 3D geometric Delaunay operations |
| [KNN_CUDA](https://github.com/gt4o4/KNN_CUDA) | CUDA-accelerated K-nearest neighbour search |
| [Zero-Shot-3DKP](https://github.com/gt4o4/Zero-Shot-3DKP) | Zero-shot 3D keypoint detection |
| [SOF](https://github.com/gt4o4/SOF) | Scene object factorization |
| [fastLayerDecomposition](https://github.com/gt4o4/fastLayerDecomposition) | Fast palette-based layer decomposition for image editing |
| [PointCloudCurvCNC](https://github.com/gt4o4/PointCloudCurvCNC) | Point-cloud curvature estimation for CNC machining |
| [Awesome-Computer-Vision-Paper-List](https://github.com/gt4o4/Awesome-Computer-Vision-Paper-List) | Curated reading list of CV papers |

---

## 🐧 Linux Systems · Kernel & Driver Development

Low-level Linux internals: out-of-tree drivers, memory management, system services, and Nix-based reproducible configurations.

| Repository | Description |
|---|---|
| [loongson-sources](https://github.com/gt4o4/loongson-sources) | Linux kernel sources for Loongson MIPS/LoongArch platforms |
| [realtek-r8125-dkms](https://github.com/gt4o4/realtek-r8125-dkms) | DKMS packaging for Realtek R8125 2.5GbE driver |
| [turbomem](https://github.com/gt4o4/turbomem) | Intel Turbo Memory (Robson) Linux driver |
| [oomd](https://github.com/gt4o4/oomd) | Userspace OOM daemon for cgroup-v2 workloads |
| [ipad_charge](https://github.com/gt4o4/ipad_charge) | Kernel module enabling fast iPad charging on Linux |
| [bindfs](https://github.com/gt4o4/bindfs) | FUSE filesystem for bind-mounting with altered permissions |
| [nix-configs](https://github.com/gt4o4/nix-configs) | Reproducible NixOS and home-manager configurations |

---

## 🌐 Advanced Networking Infrastructure

High-performance tunnelling, traffic obfuscation, DNS, and secure overlay networks.

| Repository | Description |
|---|---|
| [udp2raw](https://github.com/gt4o4/udp2raw) | UDP tunnel with traffic disguising and anti-replay protection |
| [shadowsocks-go](https://github.com/gt4o4/shadowsocks-go) | High-performance Shadowsocks proxy in Go |
| [xt_wgobfs](https://github.com/gt4o4/xt_wgobfs) | Netfilter xt_wgobfs: WireGuard traffic obfuscation kernel module |
| [rs-wgobfs](https://github.com/gt4o4/rs-wgobfs) | WireGuard obfuscation in Rust (userspace companion to xt_wgobfs) |
| [cloudflared](https://github.com/gt4o4/cloudflared) | Cloudflare Tunnel client |
| [netclient](https://github.com/gt4o4/netclient) | Netmaker network client for automated WireGuard mesh |
| [dnsforwarder](https://github.com/gt4o4/dnsforwarder) | Flexible DNS forwarder with upstream failover |
| [china-ip-list](https://github.com/gt4o4/china-ip-list) | Up-to-date China IP range list for routing and firewall rules |

---

## 🛠️ Tools & Infrastructure

| Repository | Description |
|---|---|
| [gt4o4.github.io](https://github.com/gt4o4/gt4o4.github.io) | Organization GitHub Pages site |
| [plugin-secure-shell](https://github.com/gt4o4/plugin-secure-shell) | Secure shell plugin |
| [libapps-mirror](https://github.com/gt4o4/libapps-mirror) | Mirror of Chromium hterm/libapps |
| [siyuan-shared](https://github.com/gt4o4/siyuan-shared) | Shared notes and knowledge base (SiYuan) |
| [ShiArthur03](https://github.com/gt4o4/ShiArthur03) | Personal academic archive |
| [pliss23](https://github.com/gt4o4/pliss23) | Programming Language Implementation Summer School 2023 materials |
| [SeamlessCompare](https://github.com/gt4o4/SeamlessCompare) | Evaluation harness for Meta Seamless multilingual translation models |
| [winamp](https://github.com/gt4o4/winamp) | Winamp source code mirror |

---

<p align="center">
  <a href="https://s2.hk">s2.hk</a> · <a href="https://github.com/Wenri">github.com/Wenri</a>
</p>
