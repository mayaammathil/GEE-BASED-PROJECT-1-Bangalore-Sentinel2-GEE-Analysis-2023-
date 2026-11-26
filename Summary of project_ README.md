####  Vegetation Indices considered

# 1. Enhanced Vegetation Index (EVI)
What it shows: Dense vegetation cover while reducing atmospheric scattering and soil-background interference.
Evaluation: An EVI average reflects a moderate presence of urban tree canopy, park networks, and agricultural city-fringes. Higher EVI values (green) indicate healthy forest patches like Lalbagh, Cubbon Park, or the outskirts, while low values (white/yellow) indicate roads, buildings, and paved surfaces.

# 2. Soil-Adjusted Vegetation Index (SAVI)
What it shows: Vegetation density adjusted for background soil brightness, especially helpful in semi-arid and transition zones.
Evaluation: SAVI aligns closely with the NDVI patterns but is heavily optimized to filter out dry soil backscatter typical in Bangalore's rapidly developing outer periphery. This provides a truer indicator of actual green foliage density in patchy urban-rural interfaces.

# 3. Normalized Difference Water Index (NDWI)
What it shows: Open surface water bodies and moisture-dense networks.
Evaluation: With a negative mean index value, dry land and concrete dominate the footprint. Strong positive spikes (blue) represent Bangalore's famous system of lakes (e.g., Bellandur, Ulsoor, Hebbal). If the index rises near zero, it signifies highly humid surfaces or wet soils.

# 4. Normalized Burn Ratio (NBR)
What it shows: Land dryness, bare soil exposure, and burned/devastated vegetation surfaces.
Evaluation: Healthy, hydrated green canopies reflect high positive values, while bare dirt, concrete, and dry soils drop close to or below zero. This index highlights the contrast between open grasslands/construction clearings and permanent woody vegetation.

# 5. Normalized Difference Moisture Index (NDMI)
What it shows: Canopy liquid water thickness and crop water stress levels.
Evaluation: The NDMI shows how hydrated the urban forest is. Higher values correlate to moisture-rich healthy vegetation, whereas lower values point to concrete urban heat islands or highly stressed crops on the margins during dry seasons.


#### Summary


#### 2023 Multi-Spectral Environmental Assessment of Bengaluru

This project uses 10-meter Sentinel-2 satellite data from 2023 to map and evaluate the environmental conditions of the Bengaluru Metropolitan Area (~2,187 sq km). By combining several environmental indices, we can see how the region transitions from dense concrete urban areas to pockets of green spaces and outer rural-urban borders.

# 1. Vegetation Cover and the Concrete Signature (NDVI, SAVI, and EVI)
Vegetation Density (NDVI: 0.3661 / SAVI: 0.2276): These values indicate that Bengaluru has moderate, fragmented vegetation. While there are healthy green core zones like central parks and wooded urban fringes, they are highly separated by the surrounding network of roads and concrete buildings.
The EVI Paradox (-1.9152): The mathematically impossible negative Enhanced Vegetation Index is a well-known response to dense urban environments. The high blue-wavelength reflectance from concrete, glass, and metal causes the EVI formula's denominator to become zero or negative. Far from indicating dead vegetation, this value serves as a reliable mathematical marker of highly built-up urban infrastructure.

# 2. Water Resources & Moisture Stress (NDWI and NDMI)
Surface Water (NDWI: -0.4191): The highly negative value confirms a stark lack of open surface water. Although Bengaluru is known for its beautiful lake systems, they cover a tiny fraction of the city's vast administrative footprint, which is overwhelmingly dry and paved.
Canopy Moisture (NDMI: -0.0319): An index hovering slightly below zero shows that the city's soils and plants experience mild moisture stress. This is driven by the Urban Heat Island (UHI) effect, where dry impervious surfaces prevent the ground and vegetation from retaining natural moisture.

# 3. Bare Soil & Land Clearing (NBR: 0.1173)
Soil Exposure: A low positive NBR indicates a transitional landscape on the outskirts of the city. These areas are characterized by dry soils, construction clearings, and fallow farmlands, rather than permanent, moist forest cover.

## Conclusion

Banglore presents a classic environmental profile of a rapidly expanding tropical megacity. Heavy urbanization suppresses soil and plant moisture, limits open surface water, and creates sharp spectral distortions over concrete surfaces. However, the surrounding rural-urban fringe and urban parks remain vital ecological lifelines that help buffer these environmental stresses.

