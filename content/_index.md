---
# Leave the homepage title empty to use the site title
title:
date: 2025-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: “👋 Welcome to the NbS-Geo Lab”
        content: “We focus on the application of nature-based solutions (NbS) in geological disasters.”
        align: center
        background:
          image:
            filename:  group-la2.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#666'
      - title: 2026 EGU Special Session ITS1.1/NH13.4
        content: "Artificial Intelligence for Enhancing Hydro-geological Hazard Resilience under Climate Change: Modelling, Evaluation, and Decision Support"
        align: right
        background:
          image:
            filename: 1.png
            filters:
              brightness: 0.7
          position: center
          color: '#333'
        link:
          icon: egu
          icon_pack: 
          text: Registration
          url: https://meetingorganizer.copernicus.org/EGU26/session/57761

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000

#  - block: hero
#    content:
#      title: |
#        NbS-Geo Lab
        
#      image:
#        filename: group-la2.jpg
#      text: |
#        <br>
        
 #       We focus on the application of nature-based solutions (NbS) in geological disasters
  
  - block: markdown
    content:
      title: Ni An
      subtitle: Principal Investigator
      text: |
        <div style="text-align: center; margin-top: 1rem; margin-bottom: 1rem;">
            <img src="/media/anni.jpg"
               alt="Ni An"
               style="max-width: 300px; width: 100%; height: auto; border-radius: 8px; display: block; margin: 0 auto;" />
        </div>

        <p style="max-width: 1300px; margin: 0 auto; text-align: justify;">
          Doctoral supervisor, national-level high-level overseas young talent, and outstanding young researcher in Sino-French cooperation. Graduated with a Ph.D. in Geotechnical Engineering from École National des Ponts et Chaussées, Institut Polytechnique de Paris in 2017, under the guidance of Professor Yujun Cui, an international expert in unsaturated soil mechanics. Conducted research on the interaction between the atmosphere and soil, as well as field tests, laboratory experiments, and numerical calculations of soil thermal, hydraulic, mechanical responses under extreme weather conditions. After obtaining the Ph.D., worked at the Centre for Environmental Geotechnics, Cardiff University, under the supervision of Professor H.R. Thomas, a fellow of the Royal Society and the Royal Academy of Engineering, and an academician of the Chinese Academy of Sciences, focusing on the development and application of multi-field coupling models of heat, water, gas, force, and chemistry in geotechnical materials. Joined the Institute of Disaster Prevention Engineering, College of Civil Engineering and Architecture, Zhejiang University in 2021 as a "Hundred Talents Program" researcher. Has led and participated in over ten research projects including the national-level high-level overseas young talent program and the National Natural Science Foundation of China.
        </p>


        <p style="max-width: 1300px; margin: 1rem auto 0; text-align: justify;">
          The research direction is engineering geological environment and disasters, including the influence of climate change and extreme climate conditions on the near-surface multi-field environment, the interaction process of atmosphere-plant-soil, the mechanism of mass landslide disasters and ecological prevention and control measures, the extended application of artificial intelligence algorithms in engineering geology/rock and soil engineering, and the multi-field response of rock and soil bodies to heat, water, force, and biological/chemical factors. 
          So far, I have published over 30 papers in journals such as Engineering Geology, International Journal of Coal Geology, Computers and Geotechnics, Fuel, Journal of Environmental Management, and Journal of Cleaner Production, which are in the fields of engineering geology, geotechnical engineering, and energy engineering. The average impact factor of these journals is 5.9. I serve as the part-time deputy secretary-general of the International Affairs Department of the Chinese Society for Rock Mechanics and Engineering, an editorial board member of the Canadian Geotechnical Journal, a council member of the Landslide and Engineering Slope Branch of the Chinese Society for Rock Mechanics and Engineering, a young editorial board member of the Journal of Earth Environment, a young editorial board member of the international journal Deep Underground Science and Engineering, a part-time editor of the Journal of Rock Mechanics and Geotechnical Engineering (English Edition), and a reviewer for over 20 international SCI journals and international conferences.
          <br><br>

          Personal Homepage Link: https://www.researchgate.net/profile/Ni-An; 
          https://scholar.google.co.uk/citations?user=iO3FNFUAAAAJ&hl=en
        </p>

    design:
      columns: '1'



  - block: collection  #从内容库里（如 content/post/、content/publication/ 等）自动拉取若干条，按指定样式显示。
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc  #排序方向（默认按发布日期），desc = 新到旧。
      page_type: post  #决定从哪个内容库取数据
    design:
      view: card
      columns: '1'

  - block: collection
    active: true
    content:
      title: Latest Publications
      count: 5
      align: center
      filters:
        exclude_featured: false
      page_type: publication
      order: desc
    design:
      view: citation            # 论文引用风格
      columns: 1

  - block: markdown
    content:
      title: Project
      subtitle: 
      align: left
      text: |
        1. EU-Wales FLEXIS New Energy Research Project.
        2. EU RFCS Project "MEGA+": Development and Application of Methane Extraction and Coal Gasification Technologies in Deep Rock Formations.
        3. ANDRA Project (French National Radioactive Waste Management Agency): Study on the Impact of Climatic Conditions on the Overlying Soil Layer of Shallow Radioactive Waste Disposal Repositories.
        4. EU Action COST-TU1202 "Impact of Climate Change on Engineered Slopes in Infrastructure".
        5. EU-Marie Skłodowska-Curie IRSES Project "GREAT": Research on Geotechnical Engineering Issues Related to Climate Change.
        6. Key Technology for Accurate Identification and Defense of Rainfall-Induced Group Landslide Risks in Southeast China. National Key R&D Program of China.
        7. Mechanism of Moisture Migration in Unsaturated Residual Soil Under Evaporation and Its Impact on Rainfall Threshold of Landslides. National Natural Science Foundation of China.
        8. Study on Preferential Flow Characteristics and Slope Hydrological Response of Vegetated Slopes in Hilly and Mountainous Areas of Southern China. Key Laboratory of Coupling Processes and Effects of Natural Resources.
        9. Special Research on Investigation and Monitoring of Preferential Flow Development Characteristics in Slopes with High Vegetation Coverage. China Geological Survey.
        10. Study on Key Technologies for Low-Carbon and High-Value Resource Utilization of Drilling Slag in Pile Foundation Engineering. Jiaxing Transportation Investment Group.
        11. Research and Application of Key Technologies for Resource Utilization of Construction Waste Residue. Zhejiang Communications Construction Group.
        12. Initiation Mechanism and Susceptibility Analysis of Group Landslides in Areas with High Vegetation Coverage. Zhejiang University.


#  - block: markdown
#    content:
#      title:
#      subtitle: ''
 #     text:
 #   design:
 #     columns: '1'
 #     background:
 #       image: 
 #         filename: coders.jpg
 #         filters:
 #           brightness: 1
#        parallax: false  #是否启用视差滚动
 #         position: center
 ##        size: cover
 #         text_color_light: true
 #     spacing:
 #       padding: ['20px', '0', '20px', '0']   #内容块的内边距，顺序是上右下左
 #     css_class: fullscreen


 # - block: collection
 #   content:
 #     title: Latest Preprints
 #     text: ""
 #     count: 5
 #     filters:
 #       folders:
#          - publication
  #      publication_type: 'article'
  #  design:
 #     view: citation
 #     columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
