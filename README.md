# Master-Thesis

## Title

Development of an interaction concept for efficient multimedia annotations to 3D models in Augmented Reality

## Abstract

Recent advancements in immersive technologies have introduced new possibilities to use Augmented Reality (AR) or Virtual Reality (VR) to visualize 3D models in the design review process. Research has also shown that many different industries utilize these technologies to perform design reviews. However, how feedback can be provided to 3D models and how the provided feedback can be saved to share with distributed designers or other stakeholders has not yet been investigated. There is thus a need for the use of this technology that enables feedback provision to 3D models and documentation provision of this feedback.

In this thesis, an interactive feedback solution is developed to efficiently provide multimedia annotations to 3D models in AR-based design reviews. The solution is developed in such a way that 3D models can be visualized interactively, and multimedia annotations can be provided to 3D models efficiently and intuitively. This solution also provides a mechanism to document feedback in AR to share it with dispersed stakeholders and provides a mechanism to recreate it easily. The developed feedback solution is then tested with different 3D models using the Unity game engine. This solution is evaluated to check whether the product design's common aspects can be reviewed and annotated in the AR-based product design review process. The evaluation results show that the developed feedback solution can visualize all the aspects of the product design and provide annotations to any 3D models. Moreover, the results also proved that annotations can be documented systematically and recreated efficiently in an AR environment.

## Motivation

The Product Development Process (PDP) is the process of bringing a new product idea to market. It generally includes requirements gathering, conceptual design, engineering, manufacturing, and release. The ultimate goal of the PDP is to develop a product that can cultivate, maintain, and increase a company's market value by satisfying the customers' requirements [1](https://books.google.de/books?hl=en&lr=&id=Yk6eDwAAQBAJ&oi=fnd&pg=PA105&dq=Facilitating+user+involvement+in+product+design+through+virtual+reality.&ots=QMSeuTSrYr&sig=JQdt3yPlhrDHCyUvs-IP233xAJE#v=onepage&q=Facilitating%20user%20involvement%20in%20product%20design%20through%20virtual%20reality.&f=false). Hence, iterative and regular validation of the product by the customers before the actual market release is a necessary step to achieve this goal. 

Agile development methodologies are used which focus on improving customer satisfaction, adapting to dynamic requirements, frequently delivering working software and close collaboration of customers and developers as shown in Figure [Agile development methodology](#Agile development methodology). It is an adaptive approach to product planning and implementation so that organizations can quickly respond to the feedback and build products that customers expect. It concentrates on creating a minimum viable product that goes through several iterations before anything is final. Agile development also enables the customers to validate the development status of the product regularly and can provide feedback that can be used in the next development cycle. Integrating customer knowledge in the research and development phase is a way of refining products before market launch. In short, in any product's success, accumulation and analysis of customers' feedback is an important task that can be done in design reviews.

A design review is a milestone within a PDP where designers and customers evaluate the proposed design prototype against its specified requirements to find out any possible failures. Design reviews improve the design quality of the product as well as speed up the planning process, which leads to quicker delivery of the product in the market. Such design review processes involve a large number of stakeholders representing different skills and interests. These stakeholders need to work together to develop a new product that requires excellent collaboration between them. Often, people who are involved in design review meetings are geographically separated, which makes the collaboration task more tedious. Research has shown that a lack of collaboration can lead to a waste of cost and time [2](https://d1wqtxts1xzle7.cloudfront.net/48424599/2006an_20evaluation_20of_20current_20collaborative_20prototyping_20practices_20within_20the_20AEC_20industrya_20survey_20article.pdf?1472525339=&response-content-disposition=inline%3B+filename%3DAn_evaluation_of_current_collaborative_p.pdf&Expires=1616146989&Signature=asC7ft1LPt9K8~c1roEYMfg7OEOSygBlxUWceSFW7JBAfGc~DfmgYWueJR2djrL9wuQ26s0bUeTdNuggjcqB8YKQBL48rsgrm2vwdL-SrbSkzGshbZBfpFsZ5R3M-EZJ5ArXD~u8sRr7bN1XefYaF1D9r~URSGWeNGHAlvQbgFNsbp9TRtAm5EubEITpiVHxMSSXxjpDh3guFvOe9YBk2vApKaVCfT3jzXYTxmHoRw0cS5BWbhhrwq9BRe~rKLbh0lLRswWXZWn6GOOTJmh~rLGSNBFGwa5sKuUtlxLf8cNz28FKhwvcPzCWtRLvptZUlvCqTqHYBFiUTRdypVn15w__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA).

![Agile development methodology](/agile.jpg)
<a name="Agile development methodology"></a>
[Agile development methodology](https://humanpixel.com.au/the-advantages-of-using-agile-methodology-in-software-development/)

Typically, communication mediums like sketches and images are part of design review activities which can be difficult if stakeholders are present geographically at different places \cite{thalen2012facilitating}. Such communication mediums are not intuitive enough and do not support interactive behavior. Alternatives like video conferencing software could be used as a source of communication to conduct design reviews remotely. A physical prototype can also be used for design reviews but they are expensive and time-consuming to produce which eventually delays product launch to the market. Therefore, to bring all the people involved in design review together and make use of time effectively to address design issues, new collaborative environments are needed to provide better communication and validation.

Immersive technology has the potential to provide effective communication and collaborative solutions. Augmented Reality (AR) is one of the immersive technologies which has the potential to provide collaborative solutions for design reviews \cite{ong2011augmented}. It facilitates designers and customers from the same or different disciplines, co-located or distributed geographically to share the augmented design environment and work together. AR also provides a better understanding of the proposed design among designers and customers. It enables them to explore the design from various viewpoints and identify flaws and errors much faster. Using AR for design reviews, customers can easily visualize the proposed product in the context of the real world, getting a sense of its true form and proportion by walking around it and seeing how it looks and operates. Also, research has shown that AR reduces the duration of the design review processes by keeping everyone focused on one issue at the same time instead of discussing different issues \cite{majumdar2006conceptual}. Thus, customers can provide feedback rapidly which results in the elimination of unnecessary delays in the development cycle. Hence, to reduce the entire process time and save resources, it is necessary to take the benefits of existing immersive technologies like AR to speed the design review process.

## Goal of the thesis

The goal of this thesis is to develop an interactive, intuitive, and efficient solution to provide feedback to 3D models using multimedia annotations in AR-based design reviews. This solution is then prototypically implemented for the Microsoft HoloLens 2. In order to achieve the goal of this thesis, systematic research needs to be done.

Hence, to achieve the goal of the thesis, first, the design review process in PDP needs to be studied thoroughly. Different approaches are being used to conduct a design review process in different industries. Hence, it is essential to find out these commonly used approaches and how they are being conducted. Also, essential things that are being considered for feedback while conducting a design review and necessary types of feedback need to be investigated in the thesis. Moreover, it is also necessary to discover the limitations of these traditional approaches and solutions to overcome these limitations.

Similarly, AR technology, its types, AR devices, features provided by AR, etc., need to be explored thoroughly. Then, AR approaches for conducting design reviews have to be studied meticulously. It is crucial to find out the most efficient and commonly used interaction modalities are used for AR-based design reviews. Also, an analysis of these approaches needs to be done to determine the challenges that arise while conducting design reviews. Based on the analysis, a concept for interactions to provide multimedia annotations to 3D models needs to be developed.

Furthermore, the developed concept needs to be used as a base to define and implement a prototype for Microsoft HoloLens 2 in this thesis. Also, an evaluation of the developed prototype should be done to conclude this thesis with a comprehensive summary and outlook.
