# Motivation: 
  - Dr. David Spivak and Dr. Ryan Wisenesky's work with Applied Category Theory for Categorical Databases
  - The main open source website: https://www.categoricaldata.net/
  - What are some data tools make use of applied category theory?
     - The GitHub Repository: https://github.com/CategoricalData --> https://github.com/CategoricalData/CQL --> https://github.com/CategoricalData/FQL, https://github.com/CategoricalData/hydra
  - The main motivating presentation: https://www.youtube.com/watch?v=bk36__qkhrk ( Categorical Databases - Topoi Institute)

  - strangely I would like arbitrary payloads, arbitary credentials that I can automagically map to opportunities. why stick to a predefinaed major, that's boring. focus on the atoms and build something new. Subset: present multiple credentials as a single credential. I thought credential chaining was related
    to this thought trail, but after more thinking it isn't. https://lists.w3.org/Archives/Public/public-credentials/2022Jun/0070.html ( I guess you still might have one credential that precedes another though). this thinking started with EISPP / Master17 / A Distributed Economy Writings
    ( http://bshambaugh.org/eispp, http://bshambaugh.org/eispp/ch_1_2_VRM/PNG/EISPP_directional_graph_2fresnel_gss_vrm2accesscontrol.png, http://bshambaugh.org/Master_17.html, http://adistributedeconomy.blogspot.com/2012/03/knowledge-discovery-with-semantic-web.html )  
    - Essentially the reflection of  EISPP et. al in the modern day is to rewrite the existing higher education / deliverables / and experience to employment pipeline to allow for heterogeneous credentials that are based on people's unique qualities and less on prexisting professions such as
      electrical, mechanical, chemical, aerospace, and industrial engineering (+ many non-stem areas) which come to represent and/or supplant one's identity/avatar in the common conciousness. Technology first; laws and culture will follow. These may be more cost effective than existing credentials since amendments
      or repairs may be more easily made without starting again from the beginning utilizing little or none of the "good" parts of prexisting credentials (if indeed they behave that way due to their nature in the societial fabric for a particualr individual).

# Questions:
  - "Some part of verifiable credentials will need to fit this definition in order for Applied Category Theory to be useful. (See attachment) I have theories, which are alluded to on GitHub." -Brent Shambaugh
    (attachment -> Section 1.3 (definition of a category) of Adowey's book: https://www.andrew.cmu.edu/course/80-413-713/notes/chap01.pdf
  - "Benjamin Braatz goes into category theory for RDF so maybe this is useful for defining a category. Steve Adowey goes into the relationship between groups and categories, so this may help relating cryptographic signatures (based on groups) to categories.
  - "The payload is a category, perhaps of RDF, which fits in the category of cryptographic signatures?"
      - note: pararphasing "A Functor embeds one category inside another". pg 107, category theory for programmers. Bartosz Milewski
        ![The Science of Functional Programming ... Sergei Winitzski -- pg 339](./resources/images/DSC_0007s.JPG) 
        More about Functors from the Science of Functional Programming by Segei Winitzski
  - Do credentials or signed payloads form a category? What are the arrows? What are the objects?
   ( You can probably find a paper of signed payloads. ECDSA signatures applied to category theory must be structure perserving?)
  - Can I embed the thinking of Benjamin Braatz Thesis of Category Theory Applied to RDF and Dr. Joshua Shinavier's and Dr. Ryan Wiseneky's  work of algebraic property graphs  and the thinking of a group as a category and ECSDA signatures applied to category theory 

# Look at the Defintion of a Group:
   - Chapter 5 - Key Exchanges, Real World Cryptography, David Wong
   - Group Theory and Its Applications to Physical Problems - Morton Hammermesh (page 6 - 7)
      ![Group Theory and Its Applications to Physical Problems - Morton Hammermesh - pg 6](./resources/images/DSC_0079.JPG)
      ![Group Theory and Its Applications to Physical Problems - Morton Hammermesh - pg 7](./resources/images/DSC_0080.JPG)

# Look at Groups Mapped to Groups:
  - See A Book of Abstract Algebra by C. Pinter, pg 91-94:
      ![A Book of Abstract Algebra, C. Pinter - pg 91](./resources/images/DSC_0058sA.JPG)
      ![A Book of Abstract Algebra, C. Pinter - pg 92](./resources/images/DSC_0058sB.JPG)
      ![A Book of Abstract Algebra, C. Pinter - pg 93](./resources/images/DSC_0056sA.JPG)
      ![A Book of Abstract Algebra, C. Pinter - pg 94](./resources/images/DSC_0056sB.JPG)

# Look at Categories Mapped to Catgories:
  - See Category Theory for Programmers by Bartosz Milewski: https://github.com/hmemcpy/milewski-ctfp-pdf
      ![Category Theory for Programmers  - pg 262](./resources/images/p262.png)
      ![Category Theory for Programmers  - pg 263](./resources/images/p263.png)
      ![Category Theory for Programmers  - pg 264](./resources/images/p264.png)
      ![Category Theory for Programmers  - pg 265](./resources/images/p265.png)
      ![Category Theory for Programmers  - pg 266](./resources/images/p266.png)
      ![Category Theory for Programmers  - pg 267](./resources/images/p267.png)
  - Expand on Bartosz's work with his Course on YouTube: https://www.youtube.com/watch?v=I8LbkfSSR58&list=PLbgaMIhjbmEnaH_LTkxLI7FMa2HsnawM_ 
    
# Look at the Definition of a Category:
  - Topoi - The Categorical Analysis of Logic
  - https://www.youtube.com/c/MJMCodrington
      - https://www.youtube.com/watch?v=P6DvIfTJhx8&list=PLm_IBvOSjN4zthQSQ_Xt6gyZJZZAPoQ6v
 - Category Theory by Steve Adowey, pg 5, section 1.3
      ![Category Theory by Steve Adowey pg 5, section 1.3](./resources/images/DSC_0059s.JPG)

# Look at Groups as Categories:
  Consider: (this turns out to be Dr. Steve Adowey's book suggested by Dr. Ryan Wisenesky)
    - https://www.andrew.cmu.edu/course/80-413-713/
      - https://www.andrew.cmu.edu/course/80-413-713/notes/chap04.pdf (begin discussion about Group Theory in Category Theory Book ... consider this for ECC and ECDSA involving groups and apply to C.T.)
     
      Steve Adowey's work seems very relevent. Also check out:
      -https://www.andrew.cmu.edu/course/80-413-713/notes/cats.pdf
      -https://www.andrew.cmu.edu/course/80-413-713/notes/chap01.pdf
      -https://www.andrew.cmu.edu/course/80-413-713/notes/chap02.pdf
      -https://www.andrew.cmu.edu/course/80-413-713/notes/chap03.pdf
      -https://www.andrew.cmu.edu/course/80-413-713/notes/chap04.pdf
      -https://www.andrew.cmu.edu/course/80-413-713/notes/chap04.pdf
      -https://www.andrew.cmu.edu/course/80-413-713/notes/chap05.pdf
   
   - Notice that in the video with Steve Adowey (https://www.youtube.com/watch?v=BF6kHD1DAeU) [ Category theory foundations 1.0 — Steve Awodey ]
       - "An isomorphism in a monoid is an element that has an inverse!"
       -  "It is easy to show that inverses are always unique when they exist."
       -  "A group is a monoid (a category with just one object) in which every arrow is an isomorphism"
       -  Paraphrasing: "In any category, an isomorphism from A to B is the following: there is a map from A to B called f and a map from B to A called g such that g after f is the identity on A and f after g is the indentity on B"
       -  Compare Adowey's definition of an isomorphism to Wikipedia's definition: https://en.wikipedia.org/wiki/Isomorphism#Category_theoretic_view
            ![Wikipedia - Isomorphism - Categoric View](./resources/images/wikipediaIsomorphismCategoricView.png)
       -  Follow The Science of Functional Programming by Sergei Winitzki for the definition of a monoid from a semigroup:
            ![The Science of Functional Programming ... Sergei Winitzski -- pg 339](./resources/images/DSC_0063s.JPG)
            ![The Science of Functional Programming ... Sergei Winitzski -- pg 339](./resources/images/DSC_0064s.JPG)
            ![The Science of Functional Programming ... Sergei Winitzski -- pg 339](./resources/images/DSC_0066sA.JPG)
            ![The Science of Functional Programming ... Sergei Winitzski -- pg 339](./resources/images/DSC_0066sB.JPG) 

# Look at Groups Applied to Cryptography:
  - See Elliptic Curve Cryptography in Practical Cryptography for Developers:
     https://cryptobook.nakov.com/asymmetric-key-ciphers/elliptic-curve-cryptography-ecc
  - Comprare this to math in: Chapter 5 - Key Exchanges, Real World Cryptography, David Wong
      ![Real World Cryptography, Chapter 5 - Key Exchanges, Real World Cryptography, David Wong](./resources/images/DSC_0074sA.JPG)
      ![Real World Cryptography, Chapter 5 - Key Exchanges, Real World Cryptography, David Wong](./resources/images/DSC_0074sB.JPG)
      ![Real World Cryptography, Chapter 5 - Key Exchanges, Real World Cryptography, David Wong](./resources/images/DSC_0075sA.JPG)
      ![Real World Cryptography, Chapter 5 - Key Exchanges, Real World Cryptography, David Wong](./resources/images/DSC_0075sB.JPG)
      ![Real World Cryptography, Chapter 5 - Key Exchanges, Real World Cryptography, David Wong](./resources/images/DSC_0073sA.JPG)
      ![Real World Cryptography, Chapter 5 - Key Exchanges, Real World Cryptography, David Wong](./resources/images/DSC_0073sB.JPG)
  _ Chapter 7 - Signatures and Zero-Knowledge Proofs, David Wong
      ![Real World Cryptography, Chapter 7 - Signatures and Zero-Knowledge Proofs, David Wong](./resources/images/DSC_0071sA.JPG)
      ![Real World Cryptography, Chapter 7 - Signatures and Zero-Knowledge Proofs,David Wong](./resources/images/DSC_0071sB.JPG)
  
# Look at the construction of a DID document and a verifiable credential document.
  - https://www.w3.org/TR/did-core/
  - https://www.w3.org/TR/vc-data-model/
     - Give a rough overview of a verifiable credential. What is signed? (look at did-jwt-vc and another implementation using json-ld)
  - verifiable credential presentation (https://identity.foundation/presentation-exchange)
 -  Consider:
      - https://github.com/decentralized-identity/did-jwt-vc
      -  Conversion of JSON-LD VC to JWT Payload, pg 138-139, Ch 7 Verifiable Credentials, Self-Sovereign Identity, Pruekschat et al., Manning
      - "JSON-LD document
         A JSON-LD document is a serialization of an RDF dataset. See the JSON-LD Grammar section in JSON-LD 1.1 for a formal description." https://www.w3.org/TR/json-ld11/#dfn-json-ld-document
      _ JSON Web Token Format, pg 102, 5.4.1, ibid.
  - The excellent presentation by Bjorn Hamel at Identiverse: https://www.youtube.com/watch?v=Uu651GJ5YY0
  - Image for Verifiable Credentials LifeCycle. Source:  https://w3c-ccg.github.io/vc-lifecycle/
       ![Verifiable Credentials LifeCycle](./resources/images/vc_lifecycle.jpg)  

# Look at Category Theory Applied to RDF:
  - Formal Modelling and Application of Graph Transformations in the Resource Description Framework - Benjamin Braatz
      latest access: https://conexus.com/formal-modelling-and-application-of-graph-transformations-in-the-resource-description-framework/ - > ... -> https://api-depositonce.tu-berlin.de/server/api/core/bitstreams/5f0c5a05-9ef1-455c-8198-88d95e08071a/content --> Dokument_29.pdf
         - [section 1.4 Organisation of the Thesis (pp 9 - 10)]
              ![Formal Modelling and Application of Graph Transformations in the Resource Description Framework - Benjamin Braatz - page 9 - 10](./resources/images/section1.4.png)
         - [Definition 2.5 (RDFGraph) pg 14]
              ![Formal Modelling and Application of Graph Transformations in the Resource Description Framework - Benjamin Braatz - page 15](./resources/images/definition2.5.png)
         - [Definition 2.6 (Category RDFHom) pg 15]
              ![Formal Modelling and Application of Graph Transformations in the Resource Description Framework - Benjamin Braatz - page 15](./resources/images/Definition2.6.png)
         - [Proposition 2.1 (Category RDFHom) pg 16]
              ![Formal Modelling and Application of Graph Transformations in the Resource Description Framework - Benjamin Braatz - page 16](./resources/images/Proposition2.1.png)
         - [Definition 2.7 - page 18]
              ![Formal Modelling and Application of Graph Transformations in the Resource Description Framework - Benjamin Braatz - page 16](./resources/images/definition.png)
         - [Section 2.2 Semantics - Definition 2.8 - page 19]
              ![Formal Modelling and Application of Graph Transformations in the Resource Description Framework - Benjamin Braatz - page 16](./resources/images/section2.2semantics.png)
         - [Section 2.3 - Schemas - page 23]
              ![Formal Modelling and Application of Graph Transformations in the Resource Description Framework - Benjamin Braatz - page 16](./resources/images/section2.3schemas.png)
         - [5.1.2 - Integration of Schemas - page 84]
              ![Formal Modelling and Application of Graph Transformations in the Resource Description Framework - Benjamin Braatz - page 16](./resources/images/5.1.2integrationofSchemas.png)
         - References RDF Schema: https://www.w3.org/TR/rdf-schema/

        (Suggested by Dr. Ryan Wisenesky, CTO Conexus) 
      
      - I'm probably just worrying again (https://lists.w3.org/Archives/Public/public-credentials/2022Sep/0075.html)
        - Re (Wayne Chang)--> https://www.researchgate.net/publication/281367586_A_Category_Theoretic_Model_of_RDF_Ontology
           - Does this paper allow for richer vocabularies? See this comment in https://www.w3.org/TR/rdf-schema/:
              "This specification does not attempt to enumerate all the possible forms of representing the meaning of RDF classes and properties. Instead, the RDF Schema strategy is to acknowledge that there are many techniques through which the meaning of classes and properties can be described. Richer vocabulary or 'ontology' languages such as OWL [OWL2-OVERVIEW], inference rule languages and other formalisms (for example temporal logics) will each contribute to our ability to capture meaningful generalizations about data in the Web."

In light of this madness with Category Theory, also look at https://fission.codes/blog/project-cambria-overview/ since Boris Mann and Brooklyn Zelenka (who may share some sentiments but tbd) probably have a point about not overcomplicating things for developers.

Some things, like Ceramic, chose to use JSON-Schema over JSON-LD. Understand the difference between both. Start here: https://dashjoin.medium.com/json-schema-schema-org-json-ld-whats-the-difference-e30d7315686a .

How does JSON-Schema, JSON-LD and RDF compare?? JSON-LD is a serialization of RDF. JSON-Schema is ... (add something)....and how does it compare to JSON-LD.

In context also consider Layered Schema Architecture: https://github.com/cloudprivacylabs/lsa and Overlays Capture Architecture (OCA) schema specifications: https://humancolossus.foundation/blog/cjzegoi58xgpfzwxyrqlroy48dihwz . (OCA is a software architecture? not math)

Also consider any recorded presentation about Dragon (now Hydra) by Dr. Joshua Shiniver (in collaboration with Dr. Wisenesky) accessible through here: https://www.meetup.com/Category-Theory/ .  This appears based on the Paper for Algebraic Property Graphs (https://arxiv.org/abs/1909.04881).
