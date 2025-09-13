---
title: "Developing chemical kinetic models for thermochemical applications"
subtitle: "Our paper presents a systematic, general procedure for developing chemical kinetic models that addresses these challenges through a structured, hierarchical approach. The methodology we describe has been refined through extensive experience and represents current best practices in the field."

# Summary for listings and search engines
summary: "Chemical kinetic models are essential tools for understanding and predicting the behavior of fuels in various thermochemical applications, including pyrolysis, gasification, and combustion processes. However, developing these models presents significant challenges in balancing accuracy, computational efficiency, and broad applicability across different operating conditions. Our paper presents a systematic, general procedure for developing chemical kinetic models that addresses these challenges through a structured, hierarchical approach. The methodology we describe has been refined through extensive experience and represents current best practices in the field. This work represents the culmination of years of dedicated research and methodological development within our CRECK Modeling Lab, where we have been advancing the field of chemical kinetic modeling for thermochemical processes."

# Link this post with a project
projects: []

# Date published
date: '2025-09-13T00:00:00Z'

# Date updated
lastmod: '2025-09-13T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: true

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin

tags:
  - Academic
  - Kinetics
  - Fuels

categories:
  - Kinetics
  - Fuels
---

<div style="padding: 15px; border: 1px solid transparent; border-color: transparent; margin-bottom: 10px; border-radius: 4px; color: #3c763d; background-color: #dff0d8; border-color: #d6e9c6;">
Mehl M., Pelucchi M., Pratali Maffei L., Stagni A., Cuoci A., Frassoldati A., Ranzi E., Faravelli T.   

Developing chemical kinetic models for thermochemical applications    
Nature Protocols (2025)   
DOI: [10.1038/s41596-025-01195-z](https://www.nature.com/articles/s41596-025-01195-z.epdf?sharing_token=oDyL9rqJ7wW-lm1go4i0wtRgN0jAjWel9jnR3ZoTv0MRPUeCi-_3J2ebpkuDX-30PfPSvMNg6cWLI9Gx6Bmw6CJuvfYDYZ90vjIML5y3NYfB22O-rVAQUIMu6ZW8zdmQLhX4ajbhGz2YR7hSzXq_2E1slY8EwCYnGBb9gRbozxw%3D)      
</div>





Chemical kinetic models are essential tools for understanding and predicting the behavior of fuels in various thermochemical applications, including pyrolysis, gasification, and combustion processes. However, developing these models presents significant challenges in balancing accuracy, computational efficiency, and broad applicability across different operating conditions.

Our paper presents a systematic, general procedure for developing chemical kinetic models that addresses these challenges through a structured, hierarchical approach. The methodology we describe has been refined through extensive experience and represents current best practices in the field.

Our approach begins with a robust core mechanism that describes the pyrolysis and oxidation of light chemical species. From this foundation, we systematically incorporate heavier compounds using a hierarchical framework. This method starts with archetypal species—representative molecules from each class of compounds—and then extends to related molecules within those classes. A key innovation in our methodology is the development of analogy rules derived from archetypal species. These rules enable the systematic compilation of reactions and rate parameters for molecules belonging to specific chemical classes, resulting in detailed or semi-detailed reaction mechanisms. This approach ensures consistency and reliability while reducing the time and effort required for model development.

The models developed using our procedure are inherently modular in structure, allowing for easy modification and extension. This modularity is crucial for applications requiring different levels of detail or targeting specific chemical classes, making the models both flexible and maintainable.

Validation is a critical component of our methodology. We emphasize the importance of thorough validation using both literature data and novel experiments designed specifically for model testing. This dual approach ensures that models perform reliably across the intended range of applications.

Recognizing that computational efficiency is often as important as accuracy, we present systematic approaches for mechanism reduction. These include lumping techniques and flux or sensitivity analyses, which can be applied depending on the specific application requirements and computational constraints.

While our procedures incorporate significant automation, we emphasize that expert knowledge remains crucial for optimal results. The development of reaction rate rules and identification of reaction pathways require critical analysis and benefit greatly from operator experience in chemical kinetics and thermochemical processes. Models developed following our rigorous framework demonstrate superior predictivity compared to mechanisms assembled from inconsistently sourced sub-mechanisms or those based on limited datasets. This enhanced reliability enables greater confidence when extrapolating fuel behavior beyond the specific conditions used for validation, a critical advantage for practical applications.
Impact and Future Directions
