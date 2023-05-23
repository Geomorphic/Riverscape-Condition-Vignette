# Riverscape Condition
*A Research Vignette Gist*

--------
**Author** - Jeff Anderson

**Date** - May 12, 2023

**Study Site(s)** - Kelvin Creek, Southwestern Vancouver Island, British Columbia

**Project** - Developing a Protocol for the Assessment of Riverscape Condition


------


## Question / Problem
Low-Tech, Process-Based Restoration (Wheaton et al., 2019) has gained rapid attention as it continues to demonstrate benefits to both people and nature. Similarly, the River Styles Framework (RSF; Brierley and Fryirs, 2005) has gained significant attention in its ability to provide guidance to restoration planning.  However, these advances in riverscape science have largely focused on desktop tools that produce standardized outputs at the watershed and network scales (e.g., RSF, GUT, VBET) and have thus overlooked the reach and geomorphic unit scales in the assessment and validation of riverscape condition. 

Riverscape condition has become a core concept in geomorphologically informed river management (Fryirs, 2015). Brierley and Fryirs (2005, P.1) defined this term as “*the ability of a river, and its associated ecosystem* [riverscape], *to perform its natural functions.*”. Riverscape condition is Step #2 in the RSF (Brierley and Fryirs, 2005), and yet a holistic assessment of *natural function / riverscape condition* has received little attention. 

The assessment of *riverscape condition* can be partially determined through the application of geoindicators (e.g., Wheaton et al., 2019); but these do not address the entirety of riverscape condition, which is a multi-dimentional and multi-scale concept. A thoughtful assessment of riverscape condition would then have the architecture and scaffolding to accomodate this dimentionality.  

Proposed here is a framework for the assessment of riverscape condition that is both multi-dimensional and multi-scale. 

-------
## Idea / Hypothesis
<u>Statement</u>: Now that we have desktop tools capable of organizing complex riverscapes into spatially explicit, standardized products at the watershed and network scales (e.g., RSF Performa's, BRAT, etc.), we can now consider how to complement these tools with a holistic assessment of riverscape condition.

<u>Hypothesis</u>: Assessessing riverscape condition through a multi-scale approach will provide an effective and efficient framework to observe pre-to-post restoration changes to riverscape condition at the reach scale.   

-------
## Methods
The Riverscape Restoration Assessment Framework and online Tool (RiverRAFT) was designed to collect, collate and analyze multi-scale riverscape information to assist with planning, designing and implementing Low-Tech Process-Based Restoration (LTPBR) of riverscapes (Wheaton et al., 2019); and specifically, to address the assessment of riverscape condition within this process. To accomplish this, there are three components within RiverRAFT that include the: (i) QGIS Riverscape Information System (desktop), (ii) Riverscape Assessment Protocol (field), and (iii) public facing Riverscape Cloud Interface (RCI). Each is expanded upon below. 

#### 	QGIS Riverscape Information System (QRIS)

The QGIS Riverscape Information System (QRIS) is where spatial information can be compiled at the network and watershed scales. 

<u>Existing</u> layers of interest are proposed to include:

- [ ] Geology, digital elevation models (< 10m), relative elevation models, and historic aerial photography
- [ ] Land-use pressures, roads and infrastructure, stream crossings, etc. 
- [ ] Freshwater network, vegetation inventory information, fish and wildlife species of interest (e.g., listed or of cultural importance) and distributions

<u>Generated</u> spatial layers of interest are proposed to include:

- [ ] Valley setting, geomorphic setting, valley margins, reach breaks, geomorphic units, River Styles classification (Performa's' Brierley and Fryirs, 2005)
- [ ] Stream evolution model (SEM; Cluer and Thorne, 2014) and stream evolution triangle (SET; Castro and Thorne, 2019) derived in the field at the geomorphic unit scale. 
- [ ] Geoindicator: geomorphic condition, wood loading, habitat complexity, pool frequency and volume, riffle frequency, Beaver Restoration and Assessment Tool, riparian condition, and floodplain condition 
- [ ] Riverscape condition, adjustment capacity and recovery potential

 

#### 	Riverscape Assessment Protocol (RAP)

Assessment of *Riverscape condition* includes a field-based inventory physical riverscape features at the reach scale.  The *Riverscape Assessment Protocol* (RAP; Anderson, 2023)  is proposed as a standardized, field-based assessment of riverscape condition. The RAP is designed around: (i) common physical habitat measurements, along with (ii) the geoindicators presented in LTPBR textbook (Wheaton et al, 2019). 

The RAP is intended to be a rapid <u>reach-scale audit</u> of riverscape condition. The project stream was surveyed continuously from bottom to top to generate a 'complete dataset' to explore auditing potential. 

Geoindicators are defined as “*parameters used to interpret and explain system structure, function and condition” (Wheaton et al., 2019)*. A series of eight *geoindicators* are proposed to assess the riverscape condition of each reach in the Kelvin Creek watershed. The eight geoindicators used in the assessment include: (i) geomorphic condition, (ii) wood loading, (iii) habitat complexity, (iv) riffle frequency, (v) pool spacing, (vi) beaver dam frequency, (vii) riparian condition, and (viii) floodplain connectivity.  

Each geoinidcator will be reported categorically as *poor*, *moderate* or *good* at both the geomorphic unit and reach scales. Geoinidcaotrs will also be presented numerically at both the geomorphic unit and reach scales, as per unit length (#/100 m) measures. Categorical assingments of poor, moderate, and good are grounded in the literature (e.g., pool spacing as per Montgomery et al., 1995) and defensible. 

Although the geoindicators are the focus here, the RAP produces a vast array of results (100+ metrics), for example: stream incision, entrenchment, width-depth ratio, bank height, disturbance, stream cover, spawning gravels,  Wolman's Pebble Count statistics (D16, D50, D84, etc.), vegetation type and structure for floodplain and riparian zones. 

Geoindicators will be monitored before, shortly after, and each year following restoration to track riverscape condition (via geoindicators) over time. 



#### 	Riverscape Cloud Interface (RCI)

The Riverscape Cloud Interface (RCI) provides a platform to consider multi-dimensional, multi-scale, spatial, and non-spatial riverscape information, all at once, for the determination of riverscape condition. As such, the proposed platform aims to facilitate geomorphiologically informed river management, of riverscape condition, through the application of geoinidcators, and repeat monitoring. 

Input information sources for the RCI can be grouped into three broad caterories, including: (i) *mechanistic* information surrounding root causes; (ii) *non-spatial* information such as longitudinal profiles; and (iii) *spatial* information such as geoindicators. Collectively, these three layers of information contain the ingredients to determine riverscape condition at the geomorphic unit, reach, and Performa scales. Each is briefly outlined below. 

<u>Mechanistic</u> layers of interest are proposed to include:

- [ ] Watershed assessment report card (e.g., landuse pressures such as peak flow, equivalent clear cut area, road density, stream crossing density, riparian condition, landslide per km, unstable slopes, etc.)

<u>Non-Spatial</u> spatial layers of interest are proposed to include:

- [ ] Longitudinal profile showing reach breaks and areas surveyed using the RAP 
- [ ] DEM-derived cross sections for each reach (single or averaged)
- [ ] Assemblages of geomorphic units (reach-scale percentages of pools, riffles, runs, etc.) 
- [ ] Reach-scale proportion of active channel, off-channel, and floodplain areas
- [ ] Table of reach scale characteristics (Valley setting, geomorphic setting, stream gradient, reach type, planform, reach length, substrate calibre )
- [ ] Table of reach scale geoindicators (e.g., geoindicators as *poor*, *moderate*, or *good*; linear meters of SEM stages, SET influences, or REM categories per reach; riffle and pool spacing per 100m; percent active valley bottom)

<u>Spatial</u> spatial layers of interest are proposed to include:

- [ ] Field-based assessment of geoinidcators:  geomorphic condition (SEM, SET), wood loading, habitat complexity, pool frequency and volume, riffle frequency, Beaver Restoration and Assessment Tool, riparian condition, and floodplain condition
- [ ] Relative elevation model(s) (REM) for potential restoration reaches
- [ ] Field-based determination of (i) channel evolution (SEM; Cluer and Thorne, 2014), and (ii) factors influencing   channel configuration (SET; Castro and Thorne, 2018)
- [ ] Field and desktop information on current and historic beaver dams



#### 	Methodoligical Summary

Riverscape condition is a multi-dimentional concept; thus, the assessment and tools use to assess riverscape condition must have the architecture to accomodate this dimensionality. The RiverRAFT brings together many emergent and existing ideas in riverscape science for a multi-dimentional assessment of riverscape condition.

RiverRAFT has integrated:

​	(i) Cluer and Thorne's (2014) Stream Evoultion Model; 

​	(ii) Castro and Thorne's (2018) Stream Evolution Triangle; 

​	(iii) Wheaton et al., (2019)  geoindicators; 

​	(iv) Wolman and Miller's (1954) Pebble Count;

​	(v) Paul Powers (2022) suggestion on using longitudinal profiles and relative elevation models (REM); 

​	(vi) Wohl (2019) suggestion on the inclusion of wood volume in riverscape assessments; 

​	(vii) Fryirs and Brierley (2021) suggestion that riverscape condition should include the assemblages of     geomorphic units at the reach scale; 

​	(viii) Fairfax (2023) approach with mapping past and present beaver dams;

​	(ix) Portugal et al., (2015) & O'Brien and Wheaton (2015) assessment (questionairre) of geomorphic condition; 

​	(x) Skidmore and Wheatons (2022) application of adjustment capacity and recovery potential. 

​	(xi) RRNW workshop (2023) outcome was values, values, values. RiverRAFT integrates *Traditional*, *ecological* and *community* values such that each can impact the setting of goals and objectives at the reach, riverscape or network scales. 

By integrating the above emergent ideas in riverscape science with RiverRAFTs multi-dimentional platform, collectively, a thorough assessment of riverscape condition can be made at the reach, network or Performa scales. 



-------
## Preliminary Results
The project stream is located on southeastern Vancouver Island, British Columbia (Figure 1). The watershed ranges in elevation from sea level to 1800 metres. It contains several geologic groups, with 90% of the watershed underlain by the Island Plutonic Suite and Nanaimo Group. Overlying vegetation in the upper watershed Coastal Western Hemlock with Coastal Douglas-fir in the lower watershed. Kelvin Creek is a third order stream (Figure 3) with historic Coho salmon and Steelhead populations, which are now in delcine.   

![Figure01](https://github.com/Geomorphic/Images/blob/e2563adf5f335d49ac5e60ecd78b088beb3e793d/Figure01_RivCon_Vignette.png)

**Figure 1** - Southeastern Vancouver Island showing the location of the Kelvin Creek Watershed. 



#### 	1. Riverscape Character

Riverscape character is based on several inputs including the: (i) River Styles Framework (RSF; Brierley and Fryirs, 2005), (ii) longitudinal profile, (iii) reach cross sections, and (iv) reach-scale assemblages of geomorphic units. Each are presented below. 

![Figure02](https://github.com/Geomorphic/Images/blob/e2563adf5f335d49ac5e60ecd78b088beb3e793d/Figure02_RivCon_Vignette.png)

**Figure 2** - Kelvin Creek, British Columbia showing low-flow condition. 



Drawing from the RSF, valley and confining margins were mapped which demonstrates that confining margins are frequent in lower Kelvin Creek (Figure 3). 

![Figure03](https://github.com/Geomorphic/Images/blob/e2563adf5f335d49ac5e60ecd78b088beb3e793d/Figure03_RivCon_Vignette.png)

**Figure 3** - Kelvin Creek showing valley and confining margins. 



Applying the RSF, valley setting, geomorphic setting, and valley configuration are each presented in Figure 4; with the addition of two additional metrics including: (i) assemblages of geomorphic units, and (ii) a longitudinal profile. Similar to a RSF Performa, Figure 4 demonstrates that [reach 1 of] Kelvin Creek lies within a larger valley setting, contains an inactive floodplain on river right, has levees on both sides, is a similar slope to upstream reaches, and is dominated by run / glide habitat with a cobble-gravel bed. 

![Figure04](https://github.com/Geomorphic/Images/blob/e2563adf5f335d49ac5e60ecd78b088beb3e793d/Figure04_RivCon_Vignette.png)

**Figure 4** - Kelvin Creek, British Columbia showing various components of riverscape character. 



One of the outputs of the RSF is valley setting, which ascribes a valley confinement classification scheme (O'Brien et al., 2019) to each reach. Applying this to Kelvin Creek reveals that lower Kelvin Creek has a high percentage of either partially confined or fully confined reaches (Figure 5). 

![Figure05](https://github.com/Geomorphic/Images/blob/e2563adf5f335d49ac5e60ecd78b088beb3e793d/Figure05_RivCon_Vignette.png)

**Figure 5** - Kelvin Creek showing valley margins and valley setting. This figure shows that Kelvin Creek is partially confined (or fully confined) throughout a majority of the lower watershed. 



An additional output of the RSF is geomorphic setting, which outlines source, transport and response reaches. Lower Kelvin Creek alternates frequently between transport and response reaches (Figure 6). 

![Figure06](https://github.com/Geomorphic/Images/blob/e2563adf5f335d49ac5e60ecd78b088beb3e793d/Figure06_RivCon_Vignette.png)

**Figure 6** - Kelvin Creek geomorphic setting. This figure shows lower Kelvin Creek alternates between transport and response. 



In summary, *Rivescape Character* results indicate that Kelvin Creek lies deep within a larger valley profile (Figure 4), resulting in frequent confining margins (Figure 3 & Figure 5) and alternating tranport and response zones (Fiugre 6). Valley planform is moderate to low,  which may contribute to the high proportion of run/glide habitat (60-70%) in the example (Figure 4). 



#### 	2. Riverscape Condition

Riverscape condition has been determined through two independent approaches, each drawing from the same RAP field data, these include the: (i) geoindicator approach and (ii) quesionaire approach. The questionaire approach has been included to provide a rough validation of the geoindicator approach. Some differences are expected between these two approaches, but overall they there should be a synergy in the messaging. 

  

**Geoindicators** - In the table below (Table 1) River Styles Performa's have not yet been determined; rather reach scale geoindicators will be used to assist the determination of River Styles Performa's. Riverscape Condition was determined using professional judgement, based not only on the geoindicators, but Riverscape Character (Section 1), longitudinal profile, assemblages of geomorphic units, etc.; however, in the table below Riverscape Condition is confined to the geoindicators in Table 1.  

Riverscape condition in lower Kelvin Creek (Reaches 1-7) was moderate to poor (Table 1). Immediately evident in Table 1 is wood loading and beaver activity, each poor across all / most reaches, respectfully. Each of the geoindicators in Table 1 are presented numerically in Appendix A. However, geoindicators such as the SEM (Cluer and Thorne, 2014), SET (Castro and Thorne, 2019), area of active channel/floodplain/inactive floodplain are not reported in Appendix A as they are the components of geomorphic condition in Table 1.  



**Table 1** - Kelvin Creek, British Columbia showing geoindicators along with the resultant riverscape condition. 

![Table1](https://github.com/Geomorphic/Images/blob/e2563adf5f335d49ac5e60ecd78b088beb3e793d/Table01_RivCon_Vignette.png)



**Questionaire** - Riverscape condition was determined following an objective process of answering pre-demtermined questions (Appendix B) designed by Portugal et al., (2015). Similar to the geoindicator approach (Table 1), the results in Table 2 can be used to group reaches into RSF Performa's, as this does a good job of showing like-for-like riverscape condition.  



**Table 2** - Kelvin Creek, British Columbia showing Riverscape Condition Questionnaire summary. 

![Table2](https://github.com/Geomorphic/Images/blob/e2563adf5f335d49ac5e60ecd78b088beb3e793d/Table02_RivCon_Vignette.png)



#### 	3. Recovery Potential

The application of *recovery potential* is not new to watershed restoration, as evidenced by the US EPA Recovery Potential Screening (RPS) program and its inclusion in the RSF (Brierley and Fryirs, 2005). Skidmore and Wheaton (2022) present recovery potential in the context of the RSF (Brierley and Fryirs, 2005, 2013) insofar as identifying active and inactive floodplains as where recovery potential can effectivly occur.

The RPS program was designed to compare watershed condition with its' restorability.  Similar to the RSF, each seeks to connect *condition* with *recovery potential*. In the RiverRAFT, recovery potential is contingent upon the adjustment capcity of the riverscape. Both adjustment capacity and recovery potential are presented below.  



**Adjustment Capacity** - Adjustment capacity follows the principles in RSF with respect to river character and geomorphic condition; and adds riverscape condition [as described above] to inform the adjustment capacity of the riverscape. Thus, by integrating field-based data on reach / Performa condition, efficient and effective decisions can be made on recovery potential.   

![Figure07](https://github.com/Geomorphic/Images/blob/e2563adf5f335d49ac5e60ecd78b088beb3e793d/Figure07_RivCon_Vignette.png)

**Figure 7** - Kelvin Creek showing adjustment capacity. 



**Recovery Potential** - In the RiverRAFT, recovery potential builds upon the RSF (Brierley and Fryirs, 2005, 2013) and Skidmore and Wheaton (2022) by including values. RiverRAFT has the architecture to accommodate Traditional, Ecological and Community values in the determination of recovery potential. 

The recovery potential of Reach 1[Kelvin Creek] is restricted to active floodplains in the early stages of the project. Through community engagement and landowner support, recovery potential may be expanded to include portions of the inactive floodplain (high valued agricultural properties). The RCI within RiverRAFT is intended to be public-facing so that communty values can be shared and incorporated in the riverscape restoration process.  



![Figure08](https://github.com/Geomorphic/Images/blob/e2563adf5f335d49ac5e60ecd78b088beb3e793d/Figure08_RivCon_Vignette.png)

**Figure 8** - Kelvin Creek showing valley margins, geomorphic units, and recovery potential. 



#### 	Results Summary

Riverscape condition is a multi-dimentional concept; thus, the tools use to assess riverscape condition must match this dimentionality. Presented here was a suite of tools used to define riverscape condition within the context of the RSF and the need to have field-informed validation of riverscape information. 

*Riverscape Character* (Section 1) applied Step 1 of the of the RSF and introduced longitudinal profile and the assemblages of geomorphic units to this [RSF] step. *Riverscape Condition* (Section 2) builds upon Step 2 of the RSF by introducing field-informed geoindicators to this [RSF] step. *Recovery Potential* (Section 3) builds upon Step 3 of the RSF by introducing: (i) field-informed geoindicaots into consideration of adjustment capacity; and (ii) *traditional, ecological* and *community* values into consideratio of recovery potential.    





-------
## Preliminary Interpretations
Overall, Kelvin Creek appears to be in poor to moderate condition. Planar habitat perpeturates most reaches and is not providing sufficient pool-riffle sequences for spawning and rearing salmon. Structural starvation appears to be a [secondary] driver transitioning Kelvin Creek from pool-riffle to plane bed stream type. This is evidenced in the planform by low sinuosity. 



-------
## Future Work and Questions

Can a reach-scale audit [RAP] of geoindicators [Table 1] detect riverscape change over time? 



-------
## References

- Brierley, G. J., & Fryirs, K. A. (2005). *Geomorphology and River Management: Applications of the River Styles Framework*. John Wiley & Sons.

- Castro, J., & Thorne, C. (2019). The stream evolution triangle: Integrating geology, hydrology, and biology. *River Research and Applications*, *35*. https://doi.org/10.1002/rra.3421

- Cluer, B., & Thorne, C. (2014). A stream evolution model integrating habitat and ecosystem benefits: SEM incorporating habitat and ecosystem benefits. *River Research and Applications*, *30*(2), Article 2. https://doi.org/10.1002/rra.2631

- Fairfax, Emily. (2023). *Building Climate Resiliency in a Warming World: From Beaver Dams to Undergraduate Education - ProQuest*. https://www.proquest.com/openview/e0eeb467bcffbf40ad104d27a7480def/1?pq-origsite=gscholar&cbl=18750&diss=y

- Fryirs, K. A., & Brierley, G. J. (2013). *Geomorphic Analysis of River Systems: An Approach to Reading the Landscape*. John Wiley & Sons.

- Fryirs, Kirstie & Brierly, Gary. (2021). *Assemblages of geomorphic units: A building block approach to analysis and interpretation of river character, behaviour, condition and recovery*. https://doi.org/10.1002/esp.5264

- Montgomery, D., Buffington, J., Woodsmith, R., Schmidt, K., & Pess, G. (1995). Pool Spacing in Forest Channels. *Water Resources Research - WATER RESOUR RES*, *31*, 1097–1106. https://doi.org/10.1029/94WR03285

- O’Brien, G. R., Wheaton, J. M., Fryirs, K., Macfarlane, W. W., Brierley, G., Whitehead, K., Gilbert, J., & Volk, C. (2019). Mapping valley bottom confinement at the network scale. *Earth Surface Processes and Landforms*, *44*(9), Article 9. https://doi.org/10.1002/esp.4615

- O’Brien, G., & Wheaton, J. (2015). *River Styles® Report for the Middle Fork John Day Watershed, Oregon*. https://doi.org/10.13140/2.1.3251.2329

- Portugal, E., Wheaton, J., & Bouwes, N. (2015). *Pine Creek Watershed Scoping Plan for Restoration: Using Beaver Dam Analogs and High-Density LWD to Initiate Process-Based Stream Recovery*. https://doi.org/10.13140/RG.2.1.1607.9527

- Skidmore, P., & Wheaton, J. (2022). Riverscapes as natural infrastructure: Meeting challenges of climate adaptation and ecosystem restoration. *Anthropocene*, *38*, 100334. https://doi.org/10.1016/j.ancene.2022.100334

- Wheaton, J., Bennett, S., Bouwes, N., Maestas, J., & Shahverdian, S. (2019). *Low-Tech Process-Based Restoration of Riverscapes: Design Manual. Version 1.0*. https://doi.org/10.13140/RG.2.2.19590.63049/2

- Wohl, E. (2019). Forgotten Legacies: Understanding and Mitigating Historical Human Alterations of River Corridors. *Water Resources Research*, *55*. https://doi.org/10.1029/2018WR024433

  





-------

## Appendix A - Geoindicators



![AppdxA01](https://github.com/Geomorphic/Images/blob/e2563adf5f335d49ac5e60ecd78b088beb3e793d/AppdxA01_RivC0n_Vignette.png)

![AppdxA01](https://github.com/Geomorphic/Images/blob/e2563adf5f335d49ac5e60ecd78b088beb3e793d/AppdxA02_RivCon_Vignette.png)

![AppdxA01](https://github.com/Geomorphic/Images/blob/e2563adf5f335d49ac5e60ecd78b088beb3e793d/AppdxA03_RivCon_Vignette.png)

![AppdxA01](https://github.com/Geomorphic/Images/blob/e2563adf5f335d49ac5e60ecd78b088beb3e793d/AppdxA04_RivCon_Vignette.png)

![AppdxA01](https://github.com/Geomorphic/Images/blob/e2563adf5f335d49ac5e60ecd78b088beb3e793d/AppdxA05_RivCon_Vignette.png)

![AppdxA01](https://github.com/Geomorphic/Images/blob/e2563adf5f335d49ac5e60ecd78b088beb3e793d/AppdxA06_RivCon_Vignette.png)

![AppdxA01](https://github.com/Geomorphic/Images/blob/e2563adf5f335d49ac5e60ecd78b088beb3e793d/AppdxA07_RivCon_Vignette.png)





-------

## Appendix B - Questionaire



![AppdxB01](Images/AppdxB01_RivCon_Vignette.png)



