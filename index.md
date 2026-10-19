# Kong Kin Meng — Data Science Portfolio

Hi, I'm **Kong Kin Meng** (mc65281), a data science student at the **University of Macau**. This site showcases my data science projects, built with Python and Jupyter Notebooks.

## Skills
- Python (pandas, numpy)
- Data analysis & visualization (matplotlib, seaborn, geoplotlib)
- Geospatial data analysis
- Machine learning basics (linear & ridge regression, scikit-learn)

## Projects

### Global City Population Visualization
**Status:** Completed · CISC7204 course project (Activity 8.01)

**Research question:** How are the world's cities distributed geographically, and what does the distribution of large cities (population > 100,000) reveal about regional urbanization patterns?

Using `geoplotlib`, this project maps ~3.17 million city records from the GeoNames world cities database (bundled with the geoplotlib package). It renders dot-density maps of all cities, aggregates city counts by country, builds a Voronoi diagram for cities with a population above 100,000, and applies a Delaunay triangulation to the large cities of Germany and Great Britain.

**Key findings:**
- The sample covers 234 countries with a mean of ~13,564 records per country — it is a sample, not a full census.
- Only 3,527 city records report a population above 100,000; these concentrate in Europe and Asia.
- Germany and Great Britain form dense Delaunay networks of large cities, reflecting high urbanization.

![Figure 1: Global distribution of city records](images/cell5.png)
*Figure 1: Dot-density map of all ~3.17M city records in the dataset.*

![Figure 2: Voronoi diagram of large cities](images/cell11.png)
*Figure 2: Voronoi tessellation of cities with a recorded population above 100,000.*

**Repository:** [CISC7204-mc652817-2026GitHub → Tutorial08-Cities](https://github.com/kongkinmeng/CISC7204-mc652817-2026GitHub/tree/main/Tutorial08-Cities)

## Quality Checks (Practice 09, Step 4)

Before submission, the whole portfolio was reviewed — not only the visualizations:

- **Website & links checked:** the live Pages site and the project repository link were verified publicly accessible (HTTP 200).
- **Images checked:** both figure images (`images/cell5.png`, `images/cell11.png`) were verified reachable and rendering on the live site.
- **Classmate feedback:** Fong Chin Wai (MC653748) reviewed the site and suggested adding captions to the two figures to clarify what each visualization shows.
- **Improvement made & committed:** figure captions were added (commit `5feaeeb`).
- **Pre-publish review:** the Pages site was re-verified as publicly accessible after the change.

---

*Built with GitHub Pages. Last updated: October 2026.*
