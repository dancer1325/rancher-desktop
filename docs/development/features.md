# Rancher Desktop Features & status

| Symbol   | Description                                       |
|----------|---------------------------------------------------|
| ✅        | released                                          |
| 📅       | targeted \| [next] OR [later] milestone release   |
| 🌞       | ❌NOT planned yet❌<br/> maybe \| future release  |

* items |
  * [next] milestone
    * target == upcoming monthly release
      * NORMALLY | 4th Wednesday / EACH month
  * [later] milestone & [next] milestone spillover
    * target == release after
  * [next] & [later] milestones
    * might change -- based on --
      * user feedback,
      * technical challenges,
      * etc.

[next]: https://github.com/rancher-sandbox/rancher-desktop/projects/1?card_filter_query=milestone%3Anext
[later]: https://github.com/rancher-sandbox/rancher-desktop/projects/1?card_filter_query=milestone%3Alater

### OS & Platform Support

✅ Win 10/11

✅ Mac (Intel)

✅ Mac M1 (apple silicon)

✅ Linux

🌞 Linux AArch64

🌞 Windows on AArch64

🌞 Windows Containers

### Container Engines

✅  Multiple CR support (containerd, dockerd)

### Docker

✅ CLI

✅ Swarm

✅ Compose

✅ Docker-only

### Kubernetes

✅ K3s bundled

✅ Multiple versions support

### Bundled Tooling

✅ Helm

🌞 Kubectx

🌞 [kwctl]

[kwctl]: https://github.com/kubewarden/kwctl

### Image Management

✅ Build, Push, Pull & Scan images

📅 Registry Configuration

🌞 Registry Access Control

### Networking

✅ Simple VPN

📅 Restricted VPN (Ex: Cisco AnyConnect)

### Host Access

🌞 GPU

🌞 USB

### Performance & System Resources

✅ System resource allocation

🌞 Pause app to save power

### Security

✅ Signed builds

🌞 SBOM generation for images

🌞 Image Signing

🌞 Attain SLSA Level

### Troubleshooting

✅ View logs

✅ Partial Reset

✅ Factory Reset

### GUI/Installation

✅ View Containers

✅ View Images

✅ Port forwarding

✅ Auto updates

✅ Cluster exploration - Rancher Dashboard (Preview)

🌞 Container Exploration

🌞 Configuration settings

🌞 Start/Stop/Pause Containers

🌞 Silent (No-GUI) Install

🌞 CLI/Headless mode

📅 Offline (air gap) mode

✅ Rancher Desktop CLI == `rdctl` (Preview)

### IDE Compatibility

✅ VS Code extension (With dockerd(moby))

🌞 Visual Studio IDE (Needs Validation)

🌞 Eclipse (Needs Validation)

### Integration with Other Rancher Projects

✅ k3s

📅 Rancher Dashboard

🌞 Epinio

🌞 NeuVector

🌞 Marketplace

🌞 Kubewarden

### Development

✅ Open source

✅ Public roadmap
