***
### Article #12

**Summary:**
This article is written by serpent father Jaakko Leppanen and describes the performance of serpent's approach to Woodcock delta-tracking for Monte Carlo calculations.
It begins by describing how the delta-tracking routine works, how it's implemented in the Serpent code, and the performance of the code in four cases which focus on calculating homogenized multigroup constants and isotropic transmutation cross sections.

**Strengths:**
This paper is extremely interesting because it describes a major improvement that Serpent makes on other Monte Carlo codes by using delta-tracking rather than surface-to-surface ray-tracing.
It explains why Serpent was quickly adopted as a popular Monte Carlo code for reactor design applications: in addition to simplified geometry definitions specific to reactors, delta-tracking is an excellent strategy for modeling complex geometries.

**Weaknesses:**
I think that the description of delta tracking could have been made more clear by including a simple diagram of how it works at material boundaries.
I think that plots would have been more useful than tables of group constants in comparing the performance when delta-tracking was and was not used than.

***
### Article #11

**Summary:**
This paper describes the development of a parallel three-dimensional discrete ordinates algorithm for the Thinking Machine's Connection Machine model CM-200 computer.
It starts by defining the transport equation and its terms and then describes the desired mesh that will be used to solve the problem.
The authors continue to describe the CM-200 architecture and then how an ordered $S_n$ sweep can be implemented on it.

**Strengths:**
The explicit definition of every term in the transport equation was helpful, as were the diagrams used to describe how the diagonal line and diagonal plane sweeps work.

**Weaknesses:**
This paper gave very little background on discrete ordinates or why an $S_n$ algorithm on a massively parallel computer is necessary.
I thought the results tables were clear but that plots could have been more helpful in comparing performance.

***
### Article #10

**Summary:**
This paper describes plutonium multirecycling in standard PWRs loaded with evolutionary fuels.
This means that the Pu created during the irradiation of UO$_2$ fuel is reused in MOX fuel (called "monorecycling" if the process ends after this step) and then the additional Pu generated after irradiating the MOX fuel is recycled again into MOX fuel.

**Strengths:**
It's interesting to read a paper on fuel reprocessing written by researchers in France, where this is actually done.
It's a really intersting concept.

**Weaknesses:**
I'd be curious about the cost-benefit analysis of multireprocessing -- is it worth it?
I'm also curious about the proliferation risks of reprocessing multiple times.

***
### Article #9

**Summary:**
This article explores how wind, solar, and nuclear power can be used to achieve a low-carbon electricity grid while minimizing total costs while meeting market demand.
When demand is low, the most cost-efficient methods are used to produce electricity, while when demand is high, other less efficient methods are added.
The author describes technology categories that can economically meet demand, including electricity storage, firebrick resistance-heated energy storage, reactor assisted thermal heat storage, nuclear plant with thermodynamic topping cycleusing firebrick resistance-heated energy storage,and hybrid heat from a nuclear or thermal solar plant.

**Strengths:**
I appreciate that this paper includes R&D options to shape future research plans and goals.

**Weaknesses:**
I think this paper could have been more concise yet also thought that the author could have included more detail on how licensing costs would effect market competitiveness.

***
### Article #8

**Summary:**
This paper describes how SCALE6 can be used to generate problem-dependent cross sections from ENDF's problem-independent cross section data.
This can include effects such as Doppler broadening, response due to a constant flux, epithermal scatering, etc.
The paper first describes the computational methods used and then discusses verification and validation studies, using the boiling water reactor lattice cell at hot full power as an example.

**Strengths:**
This paper was interesting because I have read a lot of papers that mention that cross sections need to be generated for deterministic calculations, but I never really knew what that meant or what it involved before reading this paper.

**Weaknesses:**
I was expecting the author to go into more detail about where the cross sections come from and how they are measured.
I was also hoping for more discussion surrounding the uncertainty in cross section data and how it limits computational capabilities.
The author also assumes that the reader knows why this work is relevant and important.

***
### Article #7

(presentation available on bcourses)

***
### Article #6

**Summary:**
This article proposes accident tolerant fuel for advanced reactor design.
The motivation of this work was the accident at the Fukushima Daichii power plant in March 2011.
The authors provide a lot of background on why this is important work and which industry stakeholders are interested in the 
They give a very detailed account of the neutronics simulations performed for this work.

**Pros:**
This work is clearly very important and applicable.

**Cons:**
There are a lot of plots in this paper and little explanation of why they are important.

***
### Article #5

**Summary:**
This article proposes a "deep-burn" transmuter to transmute the transuranic (TRU) component of LWR waste in "one pass" using a gas-cooled modular helium reactor.
The paper begins by describing the proliferation risks associated with nuclear waste (it's interesting to note that this paper was written in 2002, and the authors describe Yucca Mountain contemporaneously) and introducing the design concept.
There is discussion of using thermal neutrons for transmutation as well as the TRISO particle fuel.

**Pros:**
It's really great to see a paper considering safeguards during reactor design.
It's also interesting to see a paper practically consider transmutation (considering favorable cross sections, etc.) after reading Article #4, which provided a process for evaluating potential transmutation processes.

**Cons:**
This paper provides a good overview of the deep-burn concept and technology.
It would be interesting to see more detail about economics of this design and practical steps that would need to be taken to make this a reality as well as the authors' future plans for work on deep-burn transmutation.
It would also be interesting to see some discussion of the Np isotopes.

***
### Article #4

**Summary:**
This article describes a process by which transuranic or fission product transmutation can be used to produce fission products with short or long half lives or to transform toxic fission products into shorter-lived fission products.

**Pros:**
This paper address an important issue of clean spent nuclear fuel.
I think this work also has very interesting possibility for safeguards applications -- transmuting isotopes used to produce nuclear weapons into other isotopes.

**Cons:**
Pages three and four of the paper were dedicated to charts that (I thought) seemed illegible, especially electronically.
There was little reference to or explanation of the purpose of including these charts, which I think could have been more helpful if they had included annotations showing which decays were of most interest.

***
### Article #3

**Summary:**
This is a detailed overview article of MSR technology.
It begins with a list of operational and safety advantages of MSRs over solid fuel designs.
LeBlanc then describes the history and design of MSRs as well as the increasing interest in MSR technology and changing design criteria.

**Pros:**
This paper is a great resource for a crash course on MSRs.
The diagrams are extremely clear and helpful references for understanding how MSRs work.

**Cons:**
In discussing the advantages of MSRs over solid fuel designs, LeBlanc glosses over features (i.e. plating out noble and seminoble metals) that I don't believe are fully developed for actual construction.
I also think it's important to note that we don't have sufficient chlorine cross section data to model chloride salts.
This is something I feel that we in the reactor design community consistently overlook.

***
### Article #2
Energy Options Network, "What will advanced nuclear power plants cost?"

**Summary:**
This report aims to create a standardized method of reporting LCOE for advanced reactor technology based on data submitted anonymously by eight reactor start-up companies.
It then compares the levelized cost of electricity (LCOE) for advanced reactors with that of "conventional" reactors.
Additionally, it provides an overview of types of advanced reactor designs and features that will both raise and lower their cost when compared to conventional reactors.

**Pros:**
I thought this paper was exteremely interesting and clearly explained in layperson's terms the challenges and methodologies behind assessing LCOE.
This was especially interesting since we just discussed and calculated LCOE for an NE 267 assignment.

**Cons:**
It seemed to me that a major audience for this work would be investors, who should be interested in the cost projections presented by nuclear startups.
It would be interesting to know more about the costs of Gen IV reactor research and development, which I would assume would add an enormous up-front cost, as this process should be longer for advanced reactors.
I would also be interested in how companies project licensing costs, since there is no standardied process for licensing advanced reactors.
