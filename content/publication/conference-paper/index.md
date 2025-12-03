---
title: 'PROFL: A Privacy-Preserving Federated Learning Method with Stringent Defense Against Poisoning Attacks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yisheng Zhong
  - Li-Ping Wang

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-05-09T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-07-10T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2024 27th International Conference on Computer Supported Cooperative Work in Design*
publication_short: In *CSCWD*

abstract: Federated Learning (FL) faces two major issues, privacy leakage and poisoning attacks, which may seriously undermine the reliability and security of the system. Overcoming them simultaneously poses a great challenge. This is because pri- vacy protection policies prohibit access to users’ local gradients to avoid privacy leakage, while Byzantine-robust methods necessi- tate access to these gradients to defend against poisoning attacks. To address these problems, we propose a novel privacy-preserving Byzantine-robust FL framework PROFL. PROFL is based on the two-trapdoor additional homomorphic encryption algorithm and blinding techniques to ensure the data privacy of the entire FL process. During the defense process, PROFL first utilize secure Multi-Krum algorithm to remove malicious gradients at the user level. Then, according to the Pauta criterion, we innovatively propose a statistic-based privacy-preserving defense algorithm to eliminate outlier interference at the feature level and resist impersonation poisoning attacks with stronger concealment. De- tailed theoretical analysis proves the security and efficiency of the proposed method. We conducted extensive experiments on two benchmark datasets, and PROFL improved accuracy by 39% to 75% across different attack settings compared to similar privacy-preserving robust methods, demonstrating its significant advantage in robustness.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Federated Learning
  - Poisoning Attack
  - Privacy-Preserving
  - Defense Strategy

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: 🔗IEEE
  url: https://doi.org/10.1109/CSCWD61410.2024.10580526

url_pdf: ''
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
url_poster: ''
url_project: ''
url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
<!-- 
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
