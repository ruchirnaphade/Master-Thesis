# Master-Thesis - Overview

## Title

Development of an interaction concept for efficient multimedia annotations to 3D models in Augmented Reality

## Abstract

Recent advancements in immersive technologies have introduced new possibilities to use Augmented Reality (AR) or Virtual Reality (VR) to visualize 3D models in the design review process. Research has also shown that many different industries utilize these technologies to perform design reviews. However, how feedback can be provided to 3D models and how the provided feedback can be saved to share with distributed designers or other stakeholders has not yet been investigated. There is thus a need for the use of this technology that enables feedback provision to 3D models and documentation provision of this feedback.

In this thesis, an interactive feedback solution is developed to efficiently provide multimedia annotations to 3D models in AR-based design reviews. The solution is developed in such a way that 3D models can be visualized interactively, and multimedia annotations can be provided to 3D models efficiently and intuitively. This solution also provides a mechanism to document feedback in AR to share it with dispersed stakeholders and provides a mechanism to recreate it easily. The developed feedback solution is then tested with different 3D models using the Unity game engine. This solution is evaluated to check whether the product design's common aspects can be reviewed and annotated in the AR-based product design review process. The evaluation results show that the developed feedback solution can visualize all the aspects of the product design and provide annotations to any 3D models. Moreover, the results also proved that annotations can be documented systematically and recreated efficiently in an AR environment.

## Motivation

The Product Development Process (PDP) is the process of bringing a new product idea to market. It generally includes requirements gathering, conceptual design, engineering, manufacturing, and release. The ultimate goal of the PDP is to develop a product that can cultivate, maintain, and increase a company's market value by satisfying the customers' requirements [1](https://books.google.de/books?hl=en&lr=&id=Yk6eDwAAQBAJ&oi=fnd&pg=PA105&dq=Facilitating+user+involvement+in+product+design+through+virtual+reality.&ots=QMSeuTSrYr&sig=JQdt3yPlhrDHCyUvs-IP233xAJE#v=onepage&q=Facilitating%20user%20involvement%20in%20product%20design%20through%20virtual%20reality.&f=false). Hence, iterative and regular validation of the product by the customers before the actual market release is a necessary step to achieve this goal. 

Agile development methodologies are used which focus on improving customer satisfaction, adapting to dynamic requirements, frequently delivering working software and close collaboration of customers and developers as shown in Figure below. It is an adaptive approach to product planning and implementation so that organizations can quickly respond to the feedback and build products that customers expect. It concentrates on creating a minimum viable product that goes through several iterations before anything is final. Agile development also enables the customers to validate the development status of the product regularly and can provide feedback that can be used in the next development cycle. Integrating customer knowledge in the research and development phase is a way of refining products before market launch. In short, in any product's success, accumulation and analysis of customers' feedback is an important task that can be done in design reviews.

A design review is a milestone within a PDP where designers and customers evaluate the proposed design prototype against its specified requirements to find out any possible failures. Design reviews improve the design quality of the product as well as speed up the planning process, which leads to quicker delivery of the product in the market. Such design review processes involve a large number of stakeholders representing different skills and interests. These stakeholders need to work together to develop a new product that requires excellent collaboration between them. Often, people who are involved in design review meetings are geographically separated, which makes the collaboration task more tedious. Research has shown that a lack of collaboration can lead to a waste of cost and time [2](https://d1wqtxts1xzle7.cloudfront.net/48424599/2006an_20evaluation_20of_20current_20collaborative_20prototyping_20practices_20within_20the_20AEC_20industrya_20survey_20article.pdf?1472525339=&response-content-disposition=inline%3B+filename%3DAn_evaluation_of_current_collaborative_p.pdf&Expires=1616146989&Signature=asC7ft1LPt9K8~c1roEYMfg7OEOSygBlxUWceSFW7JBAfGc~DfmgYWueJR2djrL9wuQ26s0bUeTdNuggjcqB8YKQBL48rsgrm2vwdL-SrbSkzGshbZBfpFsZ5R3M-EZJ5ArXD~u8sRr7bN1XefYaF1D9r~URSGWeNGHAlvQbgFNsbp9TRtAm5EubEITpiVHxMSSXxjpDh3guFvOe9YBk2vApKaVCfT3jzXYTxmHoRw0cS5BWbhhrwq9BRe~rKLbh0lLRswWXZWn6GOOTJmh~rLGSNBFGwa5sKuUtlxLf8cNz28FKhwvcPzCWtRLvptZUlvCqTqHYBFiUTRdypVn15w__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA).

![Agile development methodology](/agile.jpg)
[Agile development methodology](https://humanpixel.com.au/the-advantages-of-using-agile-methodology-in-software-development/)

Typically, communication mediums like sketches and images are part of design review activities which can be difficult if stakeholders are present geographically at different places [1](https://books.google.de/books?hl=en&lr=&id=Yk6eDwAAQBAJ&oi=fnd&pg=PA105&dq=Facilitating+user+involvement+in+product+design+through+virtual+reality.&ots=QMSeuTSrYr&sig=JQdt3yPlhrDHCyUvs-IP233xAJE#v=onepage&q=Facilitating%20user%20involvement%20in%20product%20design%20through%20virtual%20reality.&f=false). Such communication mediums are not intuitive enough and do not support interactive behavior. Alternatives like video conferencing software could be used as a source of communication to conduct design reviews remotely. A physical prototype can also be used for design reviews but they are expensive and time-consuming to produce which eventually delays product launch to the market. Therefore, to bring all the people involved in design review together and make use of time effectively to address design issues, new collaborative environments are needed to provide better communication and validation.

Immersive technology has the potential to provide effective communication and collaborative solutions. Augmented Reality (AR) is one of the immersive technologies which has the potential to provide collaborative solutions for design reviews [3](https://link.springer.com/chapter/10.1007/978-1-4614-0064-6_30). It facilitates designers and customers from the same or different disciplines, co-located or distributed geographically to share the augmented design environment and work together. AR also provides a better understanding of the proposed design among designers and customers. It enables them to explore the design from various viewpoints and identify flaws and errors much faster. Using AR for design reviews, customers can easily visualize the proposed product in the context of the real world, getting a sense of its true form and proportion by walking around it and seeing how it looks and operates. Also, research has shown that AR reduces the duration of the design review processes by keeping everyone focused on one issue at the same time instead of discussing different issues [4](https://itc.scix.net/pdfs/w78-2006-tf448.pdf). Thus, customers can provide feedback rapidly which results in the elimination of unnecessary delays in the development cycle. Hence, to reduce the entire process time and save resources, it is necessary to take the benefits of existing immersive technologies like AR to speed the design review process.

## Problem definition

The design review is one of the regular activities of the PDP. It has a direct impact on a product's success in the market. Recent advances in technology have shown that AR can be used to conduct design review processes more efficiently and interactively [3](https://link.springer.com/chapter/10.1007/978-1-4614-0064-6_30). However, there are several challenges and limitations that need to be addressed. 

Conventional design review processes have been aided with 2D communication mediums like images, screenshots, sketches, or computer-aided designs (CAD) where customers provide feedback with pens, keyboards, or mouse in the form of texts or drawings [4](https://vtechworks.lib.vt.edu/handle/10919/92596). However, in AR, customers are dealing with 3D environments and objects which makes it challenging to provide feedback. In the AR environment, 3D objects are nothing but an illusion of holographic content on top of the real world. Using AR devices like AR glasses, these 3D objects can be viewed from every possible angle, but the user cannot provide feedback to some components of it by simply using a pen, pencil, or computer-aided input devices. There is no straightforward way to provide feedback to these 3D objects like a conventional way. Hence, providing feedback to 3D objects in AR is an entirely different and challenging task that needs to be solved.

Another challenge for using AR in the design review process is the interaction with 3D objects. In the AR environment, users are looking at the holograms through AR glasses and these glasses enable users to interact with holograms using hand movements and gestures. These interaction modalities are simple and sufficient enough to visualize and manipulate the 3D objects. However, it is challenging to use these modalities for design reviews and to provide feedback in AR. Sometimes users need to have some input devices to make the interaction more interactive which is cumbersome and obtrusive. Hence, natural interaction with 3D objects is more complicated than traditional systems that need to be tackled. 

Another challenge is to document users' feedback and share it with designers to implement the requested changes. In AR, users deal with 3D objects and everything that is given as feedback to these 3D objects needs to be saved later along with that 3D model. Here, the first problem is to attach users' feedback to the respective component of the 3D model and the second problem is to store that whole 3D model so that it can be shared with the designer. Hence, in AR Design Review, documentation and sharing of users' feedback is a challenging task. Therefore, to use AR for the product design review process productively, issues like provision of input modality and documenting feedback need to be solved beforehand so that users can effectively provide feedback to 3D models.

## Goal

The goal of this thesis is to develop an interactive, intuitive, and efficient solution to provide feedback to 3D models using multimedia annotations in AR-based design reviews. This solution is then prototypically implemented for the Microsoft HoloLens 2. In order to achieve the goal of this thesis, systematic research needs to be done.

Hence, to achieve the goal of the thesis, first, the design review process in PDP needs to be studied thoroughly. Different approaches are being used to conduct a design review process in different industries. Hence, it is essential to find out these commonly used approaches and how they are being conducted. Also, essential things that are being considered for feedback while conducting a design review and necessary types of feedback need to be investigated in the thesis. Moreover, it is also necessary to discover the limitations of these traditional approaches and solutions to overcome these limitations.

Similarly, AR technology, its types, AR devices, features provided by AR, etc., need to be explored thoroughly. Then, AR approaches for conducting design reviews have to be studied meticulously. It is crucial to find out the most efficient and commonly used interaction modalities are used for AR-based design reviews. Also, an analysis of these approaches needs to be done to determine the challenges that arise while conducting design reviews. Based on the analysis, a concept for interactions to provide multimedia annotations to 3D models needs to be developed.

Furthermore, the developed concept needs to be used as a base to define and implement a prototype for Microsoft HoloLens 2 in this thesis. Also, an evaluation of the developed prototype should be done to conclude this thesis with a comprehensive summary and outlook.

## Requirements

AR technology has been steadily growing technology for conducting design reviews in industries by introducing interactive visualization and natural interaction techniques with 3D content through different AR devices but to use this technology's potential fully, the below-mentioned requirements need to be fulfilled.

* Interactive visualization
* Natural interaction
* Feedback provision
* Granular feedback
* Documentation of feedback
* Cross-platform usage

## Concept

The main goal of this thesis is to develop an interactive, intuitive, and efficient solution to provide feedback to 3D models using multimedia annotations in AR-based design reviews. The solution developed in this thesis is then prototypically implemented for Microsoft HoloLens 2. Providing feedback to 3D models in AR-based design reviews is a challenging task due to the absence of input modalities such as pencil, pen, keyboard, mouse, etc. This problem is addressed in this thesis and developed a solution using the interaction modalities of Microsoft HoloLens 2 to provide feedback to 3D models efficiently and interactively.

Microsoft HoloLens 2 provides different interaction modalities such as gesture, touch, grab, pinch, speech, etc., to interact with holograms. These interaction modalities are used as leverage to develop a solution for feedback provision in this thesis. Hence, multi-modal interaction techniques such as touch, gestures, and speech are used to visualize as well as annotate 3D models. These are the most common modalities in the AR environment and are considered as natural, intuitive, and easy to use. Using these modalities, 3D objects can be visualized from different viewpoints as well as manipulate.

Speech modality is considered as one of the easiest modalities to implement. Therefore, it is used to provide text annotations to 3D models in this thesis. Another annotation feature is developed in this thesis by using touch input. Using touch input, users can provide annotations to 3D models in the form of graphics with text. Gesture interaction such as air tap and hold is used for freehand drawing around the 3D objects. Moreover, using this gesture, the user can draw and rotate 3D arrows to grab attention towards a specific part of the 3D object. Also, in this thesis, the user can measure the size of the 3D objects. Here, one hand and two hand measurement scale functionalities are provided using air tap and hold gesture. Apart from feedback, visualization functionalities are offered to users in this thesis. Users can manipulate 3D objects such as move, scale, rotate as well as they can visualize every part of the 3D object using exploded model view functionality.

Although the solution developed in this thesis is for Microsoft HoloLens 2, it is developed in such a way that it can be used on other platforms such as iOS, Android, etc. It is also a requirement of the thesis to design the solution with cross-platform functionality as much as possible. Hence, the project is structured in such a way that interaction and visualization functionalities are separated from each other. Interaction functionalities are platform-specific which can work on Microsoft HoloLens 2 whereas visualization functionalities are platform independent which can be used across any platform as shown in Figure below.

![feedbackSolutionOverview](/cross-platform.JPG)
[Feedback Solution - Overview]

The feedback solution project consists of custom icons, materials, 3D models, customprefabs1, custom scenes, custom scripts, etc. The scene view of the project consists of four empty game objects namely InteractibleManager, GUI, Model and Snapshots. InteractibleManageris a starting point of the project which is responsible for instantiating toolbars dynamically at run-time with the help of scripts ToolbarManager and ObjectSpawnManager. Using these scripts,InteractibleManager instantiates toolbars under GUIgame object.  TheModelgame object is used for attaching 3D models to providefeedback. The last game object isSnapshotsgame object.  This game object is used toattach snapshots captured by users as child objects. This whole scene is saved with the name FeedbackSolutionScene under the folder named Scenes in the project. Figure 3-2gives an overview of this project structure.

![ProjectStructure](/project structure.JPG)
[Project Structure - Overview]

1. Feedback in Augmented Reality
   1. Text annotations
   2. Text annotations with graphics/icons
   3. 3D Arrow
   4. Freehand drawing
   5. One/Two-hand measurement scale

2. Efficient interaction
   1. Speech modality
   2. Gesture modality
      1. Virtual touch
      2. Air tap and hold
      
3. Documentation of feedback
   1. Snapshot
   2. XML Serialization

4. Feedback Recreation
     
## Development Tools

1. Unity 2019
2. Mixed Reality Toolkit 2.4
3. IBM Watson Speech to Text SDK

## Presentation slides

To check presentation slides, kindly open - "Master Thesis Presentation - Ruchir Naphade - 6826490.pptx" file.

## Thesis document

Available at request.
