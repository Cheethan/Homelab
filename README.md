# Homelab

This repository documents my journey of setting my first server, including guides and notes based on personal experience. It serves as a reference for the tools and steps I used throughout the process.

## Reason for Building It

Our family watches a lot of movies, which leads to downloading large volumes of media content. I needed a reliable solution to manage and organize everything efficiently. Additionally, I wanted physical access to the drives storing our photos and videos, rather than relying on third-party cloud services. A big thanks to [TechHut](https://www.youtube.com/@TechHut) for the guidance that made this setup possible.

## Requirements

- A PC or laptop
- A hard disk (internal or external)

## Server Setup

### Hardware Specifications 

- **Device:** HP Pavilion 15  
- **Processor:** Intel Core i7-8550U  
- **Memory:** 8 GB
- **Storage:** 1 TB HDD

### Operating System

- **Server OS:** [Ubuntu Server](https://ubuntu.com/download/server)

I followed this video tutorial to install and configure Ubuntu Server:  
[Ubuntu Server Setup Guide](https://youtu.be/K2m52F0S2w8?si=5OSzqiiiStJMuMUU)

## File Management

### Preferred : CasaOS

I chose [CasaOS](https://casaos.zimaspace.com/) for file management because it’s open-source and includes an App Library, which simplifies installing and managing services.

- **GitHub:** [IceWhaleTech/CasaOS](https://github.com/IceWhaleTech/CasaOS)  
- **Website & Download:** [CasaOS Official Site](https://casaos.zimaspace.com/)  
- **Video Guide:** [CasaOS Setup](https://youtu.be/_qNWpdFqLIU?si=SnM5qwoqMNNDSgvx)

### Outcome

After setup, you’ll have shared storage (1 TB in my case) accessible over your local network (LAN/WLAN).

![image](https://github.com/user-attachments/assets/dcd2e445-8fc5-4d1c-8c04-5ed22a3052a8)


## Media Server Setup

### Preferred Tool: Jellyfin

[Jellyfin](https://jellyfin.org/) is my media server of choice. It’s open-source, actively maintained, and offers a sleek, polished interface. It stands out for its excellent media metadata handling; providing an experience similar to Google TV in terms of layout and usability.

- **GitHub:** [jellyfin/jellyfin](https://github.com/jellyfin/jellyfin)  
- **Installation:**  
  - Via CasaOS App Store  
  - [Manual Installation](https://jellyfin.org/docs/general/installation/)  
- **Video Guide:** [Jellyfin Setup](https://youtu.be/eJvQKLVrmU8?si=pzzFvGuj3HJmn65x)  
- **Media Folder Structure:** [Organizing Media for Jellyfin](https://jellyfin.org/docs/general/server/media/movies)

### Outcome

Now you have your own private cloud storage and a fully functional media server all running on hardware you physically own and control. No subscriptions, no third-party cloud dependency just complete access to your data, on your terms.

### Future plans 
- Making the 1 TB storage accesable ouside of the LAN
- RAID setup



