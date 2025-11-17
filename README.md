## Product-Design-Automation-with-Solidworks

<ul>
   <li>Developed an automated, parametric fixture model in SolidWorks with dimensions and appearance driven by a single 'ProductCode' variable.</li>
   <li>Implemented a VBA macro to dynamically monitor the 'ProductCode' variable and apply corresponding display states (B2R through B4P), automating visual configuration.</li>
   <li>Utilized SolidWorks equations to drive geometry changes (height, width, flange dimensions, aircraft cable positions), mapping six product IDs to numeric inputs (1-6).</li>
   <li>Designed the fixture to be fully scalable based on user inputs, including a dynamically scaled regular polygon shape (minimum 3 sides) via the 'PolygonSides' variable.</li>
   <li>Automated the suppression/unsuppression of features (flange and aircraft cables) based on specific product code requirements.</li>
   <li>Ensured all components, including aircraft cable positioning at section inflection points, updated dynamically with changes to core variables.</li>
   <li>Documented performance considerations for the monitoring macro and provided clear usage instructions for other designers (Tools > Macros > Edit > Run StartMonitorProductCodeSpecific).</li>
   <li>Streamlined the design process, reducing manual configuration time for multiple product variants.</li>
</ul>
