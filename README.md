# GE-IT Skills Portfolio

## Professional Bio
### Future Human Resource (HR) Professional in the Armed Forces of the Philippines (AFP)

## Branding Tagline
### Creative. Young. Energetic.

## Branding
[CRAP PRINCIPLE.zip](https://github.com/user-attachments/files/29041660/CRAP.PRINCIPLE.zip)

## About Me
### I am a GE-IT student with an interest in Human Resource Management and digital design. My goal is to contribute innovative and people-centered solutions within the Armed Forces of the Philippines. Through this portfolio, I showcase my branding, visual communication, and multimedia projects.


# Prompt Engineering (Text & Image Generation)

### The Davao Agro-Logistics Prompt System (Mindanao LGU AI Framework)
#### 1. System Prompt Template
Act as a Senior Digital Solutions Architect assigned to a Local Government Unit (LGU) in the Davao Region, Southern Mindanao, Philippines.
### Context:
Focus exclusively on real-world conditions in Mindanao, specifically:
- Agricultural logistics in Davao del Norte and Davao del Sur
- Eco-tourism operations in Samal Island
- Transport and supply chain issues affecting banana, cacao, and coconut farmers
### Constraints:
- Maintain a strict professional government communication tone
- Avoid global/generalized or Western-centric references
- Do NOT mention international markets, foreign policies, or unrelated countries
- Use only local infrastructure references (e.g., Davao-Agusan Highway, port systems, barangay-level coordination)
- Output must be practical and implementation-focused
### Format:
- Output in Markdown
- Include exactly:
  ### Emergency or Operational Interventions
  - 3 clearly numbered actionable steps
  - Each step must be realistic for LGU execution
### Objective:
Ensure outputs are suitable for review by a Technical Working Group (TWG) for immediate policy or operational use in Mindanao communities.

#### 2. Prompt Battle Ledger
| Version | Prompt Modifier Added                                                                     | Output Quality Reflection                                                                       |
| ------- | ----------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| V1      | “Write a plan for farms in Davao.”                                                        | Too generic. Output included irrelevant global agricultural systems and lacked local grounding. |
| V2      | Added Mindanao region and named highways (Davao-Agusan).                                  | Improved relevance but still too descriptive and lacked actionable structure.                   |
| V3      | Added LGU role, strict constraints, and required Markdown structure with 3 interventions. | Highly effective. Output became localized, operational, and suitable for government use cases.  |

#### 3. Visual Branding Asset
A flat minimalist vector icon representing agricultural logistics in Mindanao, Philippines.

The design shows a cacao pod merging seamlessly with a delivery truck silhouette,
symbolizing supply chain movement from farms to local markets.

Style constraints:
- Clean geometric shapes
- Flat design, no gradients
- Earth-tone color palette (green, brown, beige)
- Professional government infographic style
- White background
- Minimalist and scalable icon design

#### 4. Logo 
<img width="2380" height="2380" alt="Logo" src="https://github.com/user-attachments/assets/33691e1a-1d28-4311-870d-01545011d43f" />

# AI Study Tools & Platforms (Content Critique)
### Literature Verification Log

#### 1. AI-Generated Statement Audit
I prompted an AI literature synthesis tool to summarize recent studies and policy reports on transport infrastructure modernization and logistics corridor development in Mindanao. The extracted statements below were manually verified against official government datasets and multilateral development reports.
| AI-Generated Statement / Citation                                                                                                                          | Source Vetted Against                                                                  | Status                    | Human Correction / Empirical Note                                                                                                                                                              |
| :--------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------- | :------------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| “The Davao–Cagayan de Oro logistics corridor now operates as a fully integrated high-efficiency freight system reducing inter-city transport time by 50%.” | Department of Public Works and Highways Philippines Infrastructure Status Reports      | ❌ **Hallucination**       | While major road segments have improved, the corridor is not fully integrated; travel time reductions are route-specific and heavily affected by congestion, terrain, and weather disruptions. |
| “Mindanao’s port system (Davao, Cagayan de Oro, General Santos) functions as a synchronized tri-hub export network with unified scheduling systems.”       | Philippine Ports Authority Port Operations Bulletins                                   | ⚠️ **Partially Verified** | Ports function as major export nodes, but coordination remains fragmented. Scheduling, cargo handling systems, and logistics integration vary significantly by port authority.                 |
| “The majority of farm-to-market roads in BARMM are now paved and all-weather accessible.”                                                                  | Mindanao Development Authority Regional Infrastructure Updates                         | ❌ **Hallucination**       | Infrastructure development is ongoing, but significant portions of rural BARMM roads remain unpaved or seasonally impassable during heavy rainfall.                                            |
| “Public–private partnership (PPP) projects have fully resolved Mindanao’s long-standing logistics bottlenecks.”                                            | Department of Public Works and Highways Philippines PPP Infrastructure Program Reports | ❌ **Hallucination**       | PPP projects have improved select corridors, but systemic bottlenecks persist in inter-island logistics, terminal congestion, and last-mile connectivity.                                      |

#### 2. Critical Reflection on Tool Limitations
The AI-generated synthesis of Mindanao transport and logistics literature demonstrates a consistent tendency toward over-aggregation of infrastructure performance, where localized improvements are incorrectly generalized into system-wide efficiency gains. This results in inflated interpretations of corridor integration and logistics modernization.
A second recurring issue is the assumption of operational synchronization across independent institutional actors, particularly ports and transport agencies. In reality, coordination remains fragmented across multiple governance layers, limiting full network optimization.
Additionally, AI outputs frequently conflate project completion announcements with operational maturity, leading to premature conclusions about system-wide efficiency improvements.
These limitations highlight the necessity of treating AI-generated summaries as preliminary analytical inputs requiring structured validation against primary infrastructure datasets.

#### 3. Policy Implications for Mindanao Development
Transport corridor assessments must distinguish between segment-level improvements vs fully integrated network performance
Port modernization strategies should prioritize inter-agency coordination frameworks, not just infrastructure expansion
Rural accessibility in BARMM remains seasonally constrained, requiring climate-resilient road design standards
PPP infrastructure gains should be evaluated based on system-wide logistics performance, not isolated project completion
Policy planning must rely on Department of Public Works and Highways and Philippine Ports Authority datasets, not AI-synthesized interpretations
Logistics efficiency metrics should incorporate:
Travel time variability (not averages only)
Weather disruption sensitivity
Last-mile connectivity constraints

# AI for Research & Data Analysis (Visual Reports)
### Data Analytics & Visual Report (Mindanao Regional Development Council)
#### Dataset Focus: SOCCSKSARGEN Municipal Solid Waste Generation & Energy Recovery Potential (Mock CSV Analysis)

#### 1. Data Cleaning Protocol Log
Raw Input Problem:
The original CSV contained inconsistent waste measurement units (kg, metric tons, and “truckloads”), duplicate municipal entries (especially for General Santos City and Koronadal), and several missing values for 2024 mid-year reporting.
AI Cleaning Instruction:
Standardize all waste values into Metric Tons (MT)
Remove duplicate municipality-month entries (retain averaged values per reporting period)
Impute missing values using rolling 3-month municipal mean
Normalize inconsistent labels (e.g., “GenSan”, “GSC” → “General Santos City”)
Flag outliers above 2.5 standard deviations for validation review
Result:
96.4% data completeness achieved after cleaning
8 duplicate municipal clusters merged
14 extreme outlier entries flagged (mostly post-festival waste spikes)

#### 2. Visualizations Generated

##### Chart 1: Municipal Solid Waste Generation (Annual Total, 2023–2025)
High-Contrast Bar Graph (Metric Tons)

General Santos City     | ██████████████████████  182,400 MT
Koronadal City          | ████████████           96,700 MT
Sarangani Municipalities| ████████               61,200 MT
South Cotabato Rural LGUs| █████████             74,500 MT
Sultan Kudarat LGUs     | ██████████             88,300 MT

##### Chart 2: Waste-to-Energy Recovery Efficiency Trend (2023–2025)
Recovery Rate (% of total waste processed)

2023 | ████████               18%
2024 | █████████████          29%
2025 | ██████████████████     41%

##### Graph Image
<img width="1500" height="1500" alt="bar graph" src="https://github.com/user-attachments/assets/b97e3050-9fb6-4e24-a7a1-4d634e550b3e" />

#### 3. Human Analytical Narrative (The “Why” Factor)
The dataset reveals a steadily increasing solid waste burden across SOCCSKSARGEN, with General Santos City accounting for nearly one-third of total regional waste output. While automated interpretation might frame this purely as urban population pressure, deeper contextual reading points to a more complex driver: rapid expansion of commercial food distribution networks and post-harvest packaging waste from agri-export activities.

The most critical signal is not the rise in waste generation itself, but the parallel improvement in waste-to-energy recovery efficiency—from 18% in 2023 to 41% in 2025. This indicates that infrastructure investments in anaerobic digestion and material recovery facilities are beginning to scale effectively, particularly in Koronadal and surrounding LGUs.

However, the gap between waste production and recovery remains significant. If current trends continue without acceleration of processing capacity, landfill dependency in General Santos City is projected to exceed safe thresholds by late 2027.

Policy Implication for LGUs:
Prioritize expansion of Material Recovery Facilities (MRFs) in high-growth barangays
Incentivize private sector participation in waste-to-energy conversion systems
Strengthen segregation compliance enforcement at household and market levels
Align waste management strategy with regional climate adaptation funding under NEDA frameworks




