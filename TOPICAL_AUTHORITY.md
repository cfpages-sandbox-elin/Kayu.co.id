# Topical Authority — kayu.co.id

## Role and boundary

`kayu.co.id` should become an Indonesian reference for wood as a natural material and industrial feedstock: species and anatomy, properties, moisture, conversion, veneer and panels, durability, safe handling, specification, procurement, legality, and care. The present site is commercially oriented around PT Bajra Bumi Nusantara's sawmill and panel/component products. Those transactional routes remain separate from neutral `/artikel/` knowledge pages.

The editorial boundary is explicit:

- `kayu.co.id` owns wood-material science, identification, processing, material selection, quality, durability, and wood-product procurement.
- Structural articles explain loads, grading, connection behavior, fire behavior, and the information an engineer needs, but never provide project-ready member sizes or substitute for a qualified structural engineer and current Indonesian standards.
- Furniture articles explain how wood properties affect material choice, movement, joints, and finish. Furniture styles, room planning, ergonomics, and finished-furniture buying belong to `furnitur.co.id`.
- Product pages such as `/barecore/`, `/blockboard/`, `/veneer/`, and `/plywood/` own offers, specifications actually available, quote requests, delivery terms, and supplier claims. Educational pages may support those routes but must not become disguised sales pages.
- Forestry cultivation and ecosystem management appear only where they explain origin, traceability, legality, or material properties; this is not a silviculture or investment site.

Geographic focus is Indonesia: humid-tropical service conditions, Indonesian trade names, domestic procurement and legality, and export-document context. A city deserves a page only when real climate, species supply, regulation, logistics, or a documented case changes the substance; city-name swapping is prohibited.

## Evidence audited

Audit performed 2026-07-23 against repository `cfpages-sandbox-elin/Kayu.co.id`, branch `main`, commit `8b23b9c`.

| Evidence | Observed count/state | Editorial implication |
|---|---:|---|
| `sitemap-complete.xml` | 19 URLs | Small static-export sitemap; every URL was inspected. |
| HTML files | 19 | One HTML file corresponds to each sitemap entry. |
| Homepage | 1 | Positions the company around FJL, barecore, veneer, sawmill, and community-forest supply. |
| Commercial product/service routes | 10 | `/sawmill/`, `/barecore/`, `/blockboard/`, `/doorblank/`, `/fjl-finger-joint-layer/`, `/veneer/`, three species-specific veneer routes, and `/plywood/`; `/platform/` is an additional component route, making 11 commercial routes if counted separately. |
| Product/component routes including `/platform/` | 11 | These retain transactional ownership; educational articles link to them selectively. |
| Corporate/contact/production routes | 3 | `/tentang-kami/`, `/kegiatan-produksi/`, `/kontak-kami/`. |
| Editorial archive | 1 | `/berita/` is effectively empty (about 140 extracted words, mainly chrome); it is not evidence of topical coverage. |
| Legal-policy routes | 2 | `/privacy-policy/` and `/terms-and-conditions/`. |
| Technical/upload route | 1 | `/wp-content/uploads/astra-sites/` is indexed in the sitemap despite not being reader content. |
| Location-template pages | 0 | No city-swapped sitemap pattern was found. |
| Current commercial content depth | roughly 428–878 extracted words per main product page | Useful raw taxonomy/process evidence, but several pages mix definitions, benefits, price intent, and buying claims. |
| Existing planned `/artikel/` routes | 0 | New article slugs do not currently collide with an article library. |

Observed product coverage includes albasia/sengon, jabon, and mahogany/mahoni veneer; raw, paper-backed, phenolic-backed, laid-up, reconstituted, and wood-on-wood veneer; barecore production; blockboard; doorblank/doorcore; FJL; plywood and several loosely grouped panel terms. These terms informed the map, but the existing copy is not treated as verified technical evidence.

Primary evidence anchors checked for this plan:

- [BSN catalog entry for SNI 7973:2013](https://pesta.bsn.go.id/produk/detail/9716-sni79732013) identifies the Indonesian wood-structure design specification and showed status `Berlaku` when checked. Recheck status and obtain the authorized standard before publishing clause-level guidance.
- [Permen LHK No. 8 Tahun 2021](https://jdih.menlhk.go.id/new2/uploads/files/2021pmlhk008_menlhk_06102021121117.pdf) defines the regulatory context for forest management and processing, including wood panels and legality/traceability mechanisms. Legal claims require a fresh effective-law check.
- The Ministry's [SILK/SVLK information service](https://silk.menlhk.go.id/index.php/svlk/files/1/information-data) is a primary operational source for Indonesian timber legality and FLEGT context.
- The U.S. Forest Service [Wood Handbook](https://research.fs.usda.gov/treesearch/download/37440.pdf) is a primary technical reference for wood properties and behavior; Indonesian species and climate claims still need locally relevant sources or testing.
- [ILO wood-workshop safety guidance](https://www.ilo.org/publications/safety-and-health-wood-workshop), [OSHA woodworking hazards](https://www.osha.gov/etools/woodworking/common-hazards), and [OSHA wood-dust guidance](https://www.osha.gov/etools/woodworking/production/wood-dust) support hazard identification. They are not substitutes for Indonesian occupational-safety requirements.
- [U.S. EPA composite-wood formaldehyde standards](https://www.epa.gov/formaldehyde/formaldehyde-emission-standards-composite-wood-products) explain testing, labeling, and third-party-certification concepts for products in that jurisdiction. Do not present TSCA/CARB limits as Indonesian law or transfer values between test methods.

## Existing coverage and risks

| Existing URL/pattern | Observed role/problem | Decision | Destination/owner | Verification needed |
|---|---|---|---|---|
| `/` | Corporate/product overview with environmental and technology claims | keep | Homepage owns company positioning and navigation | Verify every company, environmental, experience, and capacity claim. |
| `/sawmill/` | Sawmill service plus a short process explanation | expand | Route owns service scope and quotation; `KAY-05` owns neutral conversion knowledge | Confirm machinery, accepted log species/dimensions, tolerances, yield reporting, and service area. |
| `/barecore/` | Product, process, characteristics, and price intent mixed | expand | Route owns available barecore offer; `KAY-07` owns panel taxonomy and performance | Verify core construction, adhesive, moisture, dimensions, grade, tests, and actual uses. |
| `/blockboard/` | Product/process/benefits/price mixed | expand | Route owns available blockboard offer; `KAY-07-A03` owns neutral selection | Confirm whether the described core and faces match delivered product. |
| `/doorblank/` | Doorblank, doorcore, and finished door language overlap | expand | Route owns the supplied component; `KAY-07-A05` owns component distinctions | Define exactly what is supplied and what machining/finishing is excluded. |
| `/fjl-finger-joint-layer/` | Product page with generic use and benefit claims | expand | Route owns FJL offer; `KAY-07-A04` owns technical FJL selection | Verify finger geometry, lamella, adhesive class, moisture, strength/non-structural claim, and tolerances. |
| `/platform/` | Base panel route reuses “panel pintu” wording from another product | manual review | Route owns the actual platform/base-panel offer | Identify the component, assembly, end use, dimensions, and canonical Indonesian/English term. |
| `/veneer/` | Broad educational and commercial intent mixed | expand | Route owns available veneer; `KAY-06` owns neutral veneer science, manufacture, and selection | Verify slicing/peeling method, backing types, thickness, adhesive, grade, and installation limits. |
| `/veneer/albasia/`, `/veneer/jabon/`, `/veneer/mahogany/` | Species-specific product and price pages with similar layouts | keep | Each route owns an actually sold veneer species | Check distinct specs and real availability; do not create more species routes without product evidence. |
| `/plywood/` | Plywood page groups MDF, particleboard, blockboard, teakblock, and multipleks as “types” | expand | Route owns available plywood; `KAY-07-A01` and `KAY-07-A02` own taxonomy/comparison | Correct taxonomy and confirm actual inventory, ply construction, bond class, face grade, and certification. |
| `/kegiatan-produksi/` | Very thin corporate production page | expand | Corporate evidence/case gallery | Add dated, consented original photos and verified process captions; do not fabricate case studies. |
| `/tentang-kami/` | Company, hutan rakyat, mission, and environmental assertions | expand | Corporate/about route | Verify company identity, source relationships, licenses, certificates, and dated evidence. |
| `/berita/` | Empty archive-like page | noindex | Future editorial index only after it contains useful posts; planned hub is `/artikel/` | Confirm CMS/deployment routing and whether `/berita/` has backlinks/history before redirecting. |
| `/wp-content/uploads/astra-sites/` | Technical directory index included as a public sitemap URL | remove | None; remove from sitemap and prevent directory-index discovery | Confirm no legitimate asset depends on directory listing; return appropriate not-found response. |
| Canonicals without trailing slash while sitemap uses trailing slash | Consistency risk across all content routes | canonicalize | One chosen URL convention | Verify live redirects, canonical tags, internal links, and Cloudflare behavior before changing. |
| Repeated global “Daftar Produk” headings/content | Navigation chrome can inflate apparent overlap | keep | Shared navigation/component | Exclude chrome from content audits and structured-data claims. |

Major same-domain overlap groups are: plywood versus “all engineered panels”; veneer overview versus species sales pages; barecore versus blockboard core; doorblank versus platform/base-panel terminology; sawmill service versus neutral conversion guides; commercial price language versus neutral procurement education. The catalog assigns one owner to each informational intent.

## Coverage matrix

| Completeness lens | Topic owners | Status/reason |
|---|---|---|
| Definition, vocabulary, history | KAY-01 | Covers wood, timber/lumber/kayu gergajian, hardwood/softwood, sapwood/heartwood, and evolving industrial products. |
| Taxonomy, species, identification | KAY-01, KAY-02 | Natural classifications are separated from trade-name and species-identification decisions. |
| Anatomy, properties, mechanisms | KAY-01, KAY-02, KAY-03 | Cellular direction, density, moisture, shrinkage, and strength variability are connected. |
| Measurement, grading, defects | KAY-04 | Owns dimensions, volume, visual/mechanical grading concepts, sampling, and defect language. |
| Need recognition and survey | KAY-12, KAY-16 | Readers translate exposure/use into requirements, then inspect symptoms and condition. |
| Requirements and design | KAY-10, KAY-11, KAY-12 | Structural and fire issues are safety-gated; material specification remains distinct. |
| Comparison and selection | KAY-02, KAY-06, KAY-07, KAY-12 | Species, veneers, panels, and project criteria have distinct comparison owners. |
| Budget, procurement, legality | KAY-13, KAY-18 | Neutral due diligence and total-cost education support, but do not duplicate, quote, or invent prices. |
| Preparation, conversion, manufacture | KAY-03, KAY-05, KAY-06, KAY-07, KAY-08 | Covers drying through sawing, lamination, bonding, and emission controls. |
| Installation, commissioning, handover | KAY-10, KAY-14, KAY-15 | Covers material conditioning, interfaces, joinery/finish checks, and qualified structural acceptance. |
| Use, inspection, maintenance | KAY-14, KAY-16 | Storage/handling and installed-product care have different lifecycle owners. |
| Troubleshooting, repair, replacement | KAY-09, KAY-16 | Biological durability is separated from condition diagnosis and repair decisions. |
| Stakeholders and building/site types | KAY-10, KAY-12, KAY-13, KAY-18 | Paths exist for homeowners, designers, engineers, manufacturers, buyers, and operators. |
| Humid, rainy, coastal, retrofit context | KAY-03, KAY-09, KAY-12, KAY-14, KAY-16 | Indonesia-specific exposure is substantive, not converted into doorway pages. |
| DIY versus professional | KAY-08, KAY-10, KAY-11, KAY-15, KAY-16, KAY-17 | Every high-risk task has stop conditions and professional handoff. |
| Safety, health, fire, chemicals | KAY-08, KAY-11, KAY-17 | Claims require primary sources plus industrial hygienist, fire engineer, chemist, or K3 review as applicable. |
| Failure modes | KAY-03, KAY-09, KAY-10, KAY-11, KAY-16 | Movement, decay, connection, fire, and installed-condition failures have owner pages. |
| Standards and regulation | KAY-10, KAY-11, KAY-13, KAY-17 | Status and applicability must be reverified; no unsupported clause or threshold is permitted. |
| Environment and end of life | KAY-08, KAY-13, KAY-17 | Legality, sourcing, yields, emissions, residues, reuse, and disposal are separated. |
| Calculators, checklists, visuals | All topics; especially KAY-01, KAY-03, KAY-04, KAY-10, KAY-13, KAY-16, KAY-18 | Diagrams, specimen photos, measurement sheets, decision tables, and calculators are required where noted. |
| Case studies/news | KAY-05, KAY-14, KAY-16, KAY-17 | Only documented field/production evidence; no invented projects or trend filler. |

## Topical map

| Topic ID | Parent topic | Reader outcome | Required subtopics/questions | Evidence/formats | Boundary | Article target |
|---|---|---|---|---|---|---:|
| KAY-01 | Wood fundamentals, anatomy, and vocabulary | Understand why wood is directional, variable, and moisture-responsive, and use core Indonesian/English terms correctly | Wood vs timber/lumber; hardwood vs softwood; growth rings; grain; pores; rays; sapwood/heartwood; juvenile/reaction wood; anisotropy; density; natural variation; history from solid timber to engineered wood | Labeled anatomy diagrams; glossary; microscopy/macrophotography; primary wood-science references | Does not identify a purchase specimen (KAY-02), calculate moisture movement (KAY-03), or classify panel products (KAY-07) | 6 |
| KAY-02 | Indonesian species, trade names, and identification | Narrow a likely species and compare properties without treating color or a seller's name as proof | Botanical vs local/trade names; sengon/albasia, jabon, mahoni and other relevant species; macroscopic identifiers; density ranges; natural variability; substitution; protected/traded species; laboratory identification; suitability by property rather than prestige | Original end/face-grain photo library; authoritative species databases; decision table; expert wood-anatomist review | Does not certify legality (KAY-13), promise project suitability (KAY-12), or create sales pages for unavailable species | 6 |
| KAY-03 | Moisture, drying, shrinkage, and dimensional movement | Measure and manage moisture from green wood through service conditions | Free/bound water; moisture content; equilibrium moisture content; meter methods/correction; oven-dry reference; air/kiln drying; schedules; casehardening/checks/warp/collapse; tangential/radial/longitudinal movement; humid-tropical acclimation | Moisture-path diagram; calculator with assumptions; meter/oven photo procedure; drying-defect atlas; wood technologist review | Does not own generic defect grading (KAY-04), installed-storage procedures (KAY-14), or structural member acceptance (KAY-10) | 6 |
| KAY-04 | Dimensions, volume, grading, and defects | Read a wood specification, measure quantity, and distinguish natural feature from rejectable defect | Nominal vs actual dimensions; metric units; board volume and recovery; straightness/square; knots; checks/splits; wane; stain; insect holes; warp forms; visual vs machine grading; sampling; tolerance and acceptance records | Measurement diagrams; defect photo atlas; volume calculator; inspection sheet; applicable standard review | Does not assign structural capacity (KAY-10), diagnose active biological attack (KAY-09), or quote commercial price (existing product routes/KAY-18) | 6 |
| KAY-05 | Logs, sawmilling, and solid-wood conversion | Understand how log characteristics and sawing/drying decisions affect yield and quality | Log scaling; breakdown; flatsawn/quartersawn/riftsawn concepts; saw kerf; recovery; edging/trimming; resawing; planing; defect optimization; machinery sequence; residues; custom-sawmill brief and acceptance | Process flow; cut-pattern diagrams; yield worksheet; documented mill photos; machine/manufacturer data; K3 review | Does not sell sawmill work (`/sawmill/`), teach unsafe machine operation (KAY-17), or design finished furniture (`furnitur.co.id`) | 6 |
| KAY-06 | Veneer science, production, matching, and application | Choose and specify veneer by cut, grade, backing, matching, substrate, and service exposure | Peeling/slicing/sawing; raw and backed veneers; thickness; figure; face/back; grading; book/slip/random matching; layup; substrate; adhesive; pressing; edge/joint defects; repair; species veneers | Cut/match diagrams; sample-board photos; specification checklist; manufacturer technical data; adhesion/finish tests | Does not own offers (`/veneer/` and species routes), classify all panels (KAY-07), or teach chemical exposure without KAY-08 controls | 6 |
| KAY-07 | Plywood, barecore, blockboard, FJL, and engineered products | Correctly distinguish wood-based panels/components and select by construction and verified performance | Plywood ply/veneer orientation; multipleks terminology; barecore/blockboard; FJL; LVL/glulam/CLT orientation; MDF/particleboard/OSB distinction; face/core/bond classes; density; thickness; flatness; edge behavior; use limits | Exploded diagrams; taxonomy matrix; cross-section photos; product data and test reports; standards crosswalk | Commercial availability belongs to `/plywood/`, `/barecore/`, `/blockboard/`, `/fjl-finger-joint-layer/`, `/doorblank/`, `/platform/`; structural design belongs to KAY-10 | 6 |
| KAY-08 | Adhesives, finishes, preservatives, and indoor emissions | Ask for the right chemistry, evidence, and controls without relying on vague “waterproof” or “low emission” labels | Adhesive families and cure; bond exposure class; surface coatings; solvent/waterborne distinction; formaldehyde/emissions; test-method incompatibility; SDS/labels; VOC; preservative chemistry; compatibility; ventilation; safe handling and disposal | Chemistry matrix; SDS-reading guide; accredited-test-report checklist; primary regulator sources; chemist/industrial-hygienist review | Does not prescribe treatment recipes (KAY-09), teach finishing technique beyond material compatibility (KAY-15), or transfer foreign limits into Indonesian law | 6 |
| KAY-09 | Natural durability, fungi, termites, borers, and preservation | Diagnose likely deterioration pathway, reduce conditions that enable it, and know when treatment/replacement needs a professional | Moisture-decay relationship; staining vs decay; termite/borer signs; species/sapwood variability; design for drainage/ventilation; treatment classes; penetration/retention concepts; existing-wood treatment; monitoring; repair vs replace; environmental controls | Symptom decision tree; original macro photos; moisture map; pest/wood specialist review; current product labels and regulation | Does not identify species from damage alone (KAY-02), provide pesticide dosage (licensed label/professional), or own general repair planning (KAY-16) | 6 |
| KAY-10 | Structural timber concepts, grading, connections, and engineering handoff | Understand the evidence and design decisions needed before wood carries building loads | Loads and load paths; member orientation; grade/property values; duration/service conditions; stability; notches/holes; fasteners/connectors; connection moisture/corrosion; diaphragms/bracing; seismic context; inspection and engineer deliverables | Current authorized SNI; calculation examples clearly marked educational; connection diagrams; structural-engineer review | No project-ready sizes, capacities, connection schedules, or approval; qualified engineer owns design and acceptance; furniture joints belong to KAY-15/`furnitur.co.id` | 6 |
| KAY-11 | Wood in fire and fire-safe detailing | Understand ignition, charring, concealed hazards, compartment interfaces, and evidence needed for a fire strategy | Ignition vs fire resistance; charring and residual section concepts; surface spread/smoke; encapsulation; cavities and penetrations; connectors; coatings and treatments; workshop dust fire/explosion; inspection after fire; test reports and applicability | Fire-test report anatomy; detail diagrams; primary fire/standard sources; fire-engineer and K3 review | Does not give a universal fire rating, firefighting instruction, or structural reuse approval; KAY-10 owns structural design and KAY-17 owns workshop controls | 6 |
| KAY-12 | Material selection and wood specifications by exposure | Translate use, environment, appearance, service life, maintenance, and budget into a procurement-ready material brief | Interior/exterior; wet/humid/ground contact; coastal/hot/rainy conditions; traffic and wear; appearance grades; solid vs panel; species-property screening; finish/treatment compatibility; new build vs retrofit; sample/mockup; substitution control | Decision tree; requirement worksheet; specification template; sample approval form; architect/material specialist review | Does not rank brands or sell products (existing commercial routes), design furniture (`furnitur.co.id`), or size structural members (KAY-10) | 6 |
| KAY-13 | Legal sourcing, traceability, sustainability, and certification | Verify origin and claims, distinguish legality from sustainability, and document the chain of custody relevant to a purchase | Indonesian SVLK/S-Legalitas context; transport/supply records; species and origin; chain of custody; certification scope/validity; recycled/reclaimed wood; plantation/community forest; carbon claim boundaries; export destination requirements; fraud red flags | Current official-law links; SILK lookup walkthrough; document checklist; certification-scope diagram; legal/compliance review | Does not provide legal advice, guarantee a supplier, or teach forest investment; project price and vendor comparison belong to KAY-18 | 6 |
| KAY-14 | Storage, transport, handling, and acclimation | Prevent avoidable moisture, impact, contamination, and distortion between mill and installation | Packaging; stickers/dunnage; ground clearance; cover/ventilation; transport weather protection; flat/vertical storage; panel edge/corner protection; acclimation; moisture baseline; quarantine; lifting/manual handling; delivery inspection | Site checklist; stacking diagrams; moisture log; damage photo examples; field measurement | Does not own kiln drying (KAY-03), installed-condition diagnosis (KAY-16), or transport contract terms (KAY-18) | 6 |
| KAY-15 | Machining, joinery, fastening, and finishing interfaces | Plan safe, compatible fabrication and finishing while respecting wood movement and product limitations | Grain-aware machining; pilot holes; screw/nail behavior; glue joints; movement allowances; edge sealing; sanding sequence; finish sample; panel-edge treatment; veneer finishing; repairability; stop conditions | Detail diagrams; sample/test plan; manufacturer instructions; craft specialist and K3 review | Does not teach machine bypasses (KAY-17), design furniture style/ergonomics (`furnitur.co.id`), or provide structural connection design (KAY-10) | 6 |
| KAY-16 | Inspection, maintenance, troubleshooting, repair, and replacement | Read symptoms systematically, address cause before cosmetic repair, and decide monitor/repair/replace/escalate | Baseline records; moisture/staining/cracks/warp/delamination/loose joints; active vs historic insects; finish failure; concealed risk; cleaning; local repair; component replacement; post-flood/fire triage; professional stop conditions | Inspection route; symptom matrix; photo log; moisture readings; repair decision tree; specialist review | Biological mechanisms belong to KAY-09, structural/fire approval to KAY-10/KAY-11, and finish chemistry to KAY-08 | 6 |
| KAY-17 | Wood-industry K3, dust, fire, waste, and environmental control | Recognize manufacturing hazards and the control/evidence hierarchy for safer production | Machine guarding; lockout concepts; kickback/cutting zones; dust exposure and extraction; noise; ergonomics; adhesives/solvents; combustible dust/fire; housekeeping; wastewater/residues; offcut use; emissions; incident learning | Hazard map; hierarchy-of-controls table; primary K3 sources; documented facility data; qualified K3/industrial-hygiene/fire review | Not a machine-operation manual or legal compliance certificate; product chemistry belongs to KAY-08 and consumer maintenance to KAY-16 | 6 |
| KAY-18 | Buying wood products and evaluating suppliers | Compare quotes and suppliers on equivalent scope, evidence, risk, and lifecycle value | Requirements before quote; dimensions/grade/moisture/bond/finish; sample and test reports; quantity/yield; price components; MOQ/lead time; packaging/delivery; acceptance; warranty/claims; supplier capability; counterfeit documents; total cost | RFQ template; bid-normalization table; receiving checklist; lifecycle-cost worksheet; documented supplier evidence | Actual prices, inventory, delivery promise, and sale belong to each commercial product route; legality depth belongs to KAY-13 and technical specification to KAY-12 | 6 |

Total planned: **18 parent topics and 108 distinct article briefs**.

## Related-domain opportunities

Separate owned domains are independent editorial properties, so overlap is allowed and is not cannibalization:

| Domain/context | Useful independent viewpoint | Collaboration opportunity |
|---|---|---|
| `furnitur.co.id` | Finished furniture, ergonomics, room use, style, fabrication workflow, care | Let `kayu.co.id` explain material movement/specification; let `furnitur.co.id` explain furniture decisions. Cross-link only when useful and transparently editorial. |
| Construction/material domains | Whole-system building application, contractor scope, façade/floor/door/roof assemblies | `kayu.co.id` contributes wood-material and quality evidence; the system domain owns assembly-level design and service intent. |
| Safety/fire domains | Building fire strategy, detection, suppression, evacuation, workplace systems | `kayu.co.id` focuses on wood behavior and workshop hazards, with qualified review. |
| Sustainability/legal resources | Forestry, certification, traceability, circularity | Cite primary official/certification sources instead of manufacturing a private definition of “sustainable.” |

Do not create a cross-domain private link network for ranking. Links must be useful to readers, contextually justified, and editorially disclosed where commercial.

## Consolidation plan

1. Preserve commercial-route URLs with history; correct their taxonomy, claims, evidence, and boundaries in place.
2. Establish `/artikel/` as the neutral knowledge hub. Resolve whether `/berita/` should become that hub or redirect only after checking backlinks, live routing, and deployment capability.
3. Remove `/wp-content/uploads/astra-sites/` from the sitemap and prevent directory listing/indexation after dependency review.
4. Choose and enforce one trailing-slash/canonical convention across redirects, canonicals, sitemap, navigation, and structured data.
5. Treat `/veneer/` as the commercial veneer hub and retain the three species routes only when availability/specifications are distinct and verifiable. Informational veneer science lives in KAY-06 articles.
6. Correct `/plywood/` so MDF, particleboard, blockboard, plywood, and related products are not presented as interchangeable “types.” Point readers to KAY-07 neutral comparisons.
7. Clarify `/doorblank/` versus `/platform/` from actual supplied assemblies before publishing supporting content.
8. Do not programmatically create species, application, or city pages. Add a route only when unique evidence and stable intent justify it.
9. Add author/reviewer identity, update date, sources, methodology, and corrections mechanism to technical articles.

## Internal-link architecture

- `/artikel/` links to all 18 parent-topic hubs; each hub links to its six child briefs.
- Every article links upward to its hub and laterally to only two to four genuinely useful briefs listed in the catalog.
- KAY-01 → KAY-02/KAY-03/KAY-04 creates the fundamentals path.
- KAY-03/KAY-04 → KAY-05/KAY-06/KAY-07 explains how raw variability becomes product quality.
- KAY-07 → KAY-08/KAY-09/KAY-12 connects construction, chemistry, durability, and selection.
- KAY-10/KAY-11 are safety-gated paths. They link to KAY-12 for specification and to qualified-professional stop conditions; they do not funnel readers directly to a sale after a hazard warning.
- KAY-14 → KAY-15 → KAY-16 forms delivery, fabrication/installation, and care/repair lifecycle.
- KAY-13/KAY-18 support procurement. Commercial links appear only where an actually available product or service matches the reader's specification.
- Diagnostic pages in KAY-09 and KAY-16 link to prevention, safe isolation, repair/replacement decisions, and the relevant professional handoff.
- Existing product routes link to one neutral definition/selection article rather than a repetitive generic set. Articles link back only when the product route supplies the exact described product.

## Evidence and editorial standards

1. **Evidence hierarchy:** current Indonesian law and regulator sources; authorized current standards; accredited test reports; Indonesian research institutions/species databases; manufacturer technical data tied to a specific product; qualified expert review; documented original measurements/photos. Secondary explanations can orient but cannot establish safety thresholds.
2. **Structural gate:** any capacity, load, connection, notch/hole, stability, seismic, or acceptance claim requires current authorized SNI verification and named qualified structural-engineer review. Educational calculations must state assumptions and must not yield a construction-ready design.
3. **Fire gate:** fire-resistance, charring, flame-spread, coating/treatment, compartment, post-fire reuse, and dust-explosion content requires applicable primary standards/test evidence plus fire-engineer or K3 review. A test result applies only to the tested assembly and method.
4. **Chemical/health gate:** adhesive, coating, preservative, formaldehyde/VOC, dust-exposure, and disposal claims require current SDS/label, compatible test method, relevant jurisdiction, and chemist/industrial-hygienist/K3 review. Never compare numbers from unlike tests or present TSCA/CARB as Indonesian law.
5. **Species/property gate:** use ranges with source, moisture/test condition, and variation. Color, smell, seller name, or a single photo is not definitive identification.
6. **Legality gate:** recheck effective regulations and official systems at publication/update time. Explain that a document, logo, or certificate must be validated for issuer, holder, scope, product, site, and date.
7. **Field evidence:** do not invent projects, yields, prices, failures, customer results, or “tests.” Original photos need date/context/consent and must not reveal private data.
8. **Commercial separation:** factual educational copy cannot claim stock, grade, certification, warranty, or delivery unless the commercial route has current evidence. Disclose company involvement.
9. **Update discipline:** review safety/legal pages at least annually and on known regulatory/standard changes; date-stamp all technical reviews.
10. **AI-draft control:** verify every number, species name, test method, regulation, standard status, and causal claim against the source before human editorial approval.

## First bounded publication cluster

Publish these 12 assets first:

| Asset | Role |
|---|---|
| KAY-01-A01 | Central beginner hub: wood as an anisotropic natural material |
| KAY-01-A02 | Vocabulary bridge for Indonesian buyers/designers |
| KAY-02-A01 | Safe species-identification workflow |
| KAY-03-A01 | Moisture-content foundation |
| KAY-03-A04 | Humid-tropical dimensional-movement calculator/explainer |
| KAY-04-A03 | Visual defect atlas and acceptance language |
| KAY-07-A01 | Correct panel-product taxonomy |
| KAY-07-A02 | Plywood construction and specification |
| KAY-08-A03 | Emissions/test-report reading without false equivalence |
| KAY-09-A01 | Moisture, fungi, and decay decision path |
| KAY-12-A01 | Wood-material requirement worksheet |
| KAY-13-A01 | Indonesian legality/traceability evidence path |

This cluster is coherent because it gives a buyer or specifier one material foundation, vocabulary, identification discipline, moisture/defect controls, panel taxonomy, health/durability safeguards, a specification workflow, and legality due diligence. It also creates honest context for the site's current solid-wood, veneer, and panel routes without beginning with sales copy.

Measure:

- valid indexation and canonical selection;
- impressions/clicks grouped by distinct intent, not only aggregate ranking;
- scroll/task completion, glossary/diagram use, calculator completion, and specification-checklist use;
- contextual click-through to relevant product routes and qualified inquiries that state material/specification needs;
- editor/source corrections;
- Search Console query/page overlap and unexpected page switching;
- receiving/quote questions that show whether the educational assets reduce ambiguity.

Do not publish later waves until the first cluster is reviewed, internally linked, indexed, and producing evidence. Content count is not a success metric by itself.

## Definition of done

- All 18 topics have six distinct, non-location-swapped briefs and match the 108-row catalog.
- Every title, ID, and slug is unique; related IDs resolve; all rows state one intent, coverage promise, evidence, and a named boundary owner.
- Planned slugs are checked against the 19 current routes and future routes before implementation.
- Commercial, structural, furniture, forestry, and safety boundaries are visible in briefs and page templates.
- Existing product-route claims/taxonomy and `/wp-content/uploads/astra-sites/` sitemap exposure receive manual remediation before large-scale publication.
- Each safety-critical page passes the structural, fire, chemical/health, legality, or K3 evidence gate that applies.
- One bounded wave is published with complete hub/spoke links, schema only where supported, author/reviewer/source dates, analytics, lead attribution, and same-domain cannibalization monitoring.
- Continue, merge, revise, or stop based on task completion and qualified commercial evidence—not article volume or rankings alone.
