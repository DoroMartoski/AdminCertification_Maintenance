Spring 22 release Features
1. **Targeted Prompts**: newest type of in-app guidance that allows you to target a specific element to show your users exactly what you are refrring to.
  * Change applies to Lightning Experience in Essentials, Professional, Enterprise, Unlimited, and Developer editions.
  *  Select In-App Guidance from setup. Create Prompt and choose **Targeted Prompt** from the Prompt type area
2. **Dynamic Gauge Charts in Lightning Experience Dashboards**:
  * change applies to Lightning Experience in Essentials, Group (View Only), Professional, Enterprise, Performance, Unlimited, and Developer Editions.
  * use the Dashboard Builder to create gauge charts in either Standard or Dynamic mode.
    * **Standard mode**: 
      * selct report metric as the target
      * enter numeric vale=ues for the segment ranges
    * **dynamic mode**:
      * select field values and report measures that respond dynamically to changes in business conditions and goals
      * source report must include at least one grouping
      * Your source reports must be set up with the groupings, metrics, and filters that you want to reflect in the gauge charts.
      * For standard gauge charts, the segment values are numbers. For a dynamic gauge chart, the segment values are percentages.
      * setup the following gauge properties in the dashboard's Add Component window
        * Report metric: A metric defined in the source report, such as Record Count or Sum of Amount
        * Field: The field value from a selected Salesforce object and record. This s used as the chart target (the maximum value in the gauge).
3. **Clear Workspace Tabs for New Console Sessions**: For those using Lightning Console, your users can now start new console sessions fresh. No more loading workspaces from previous sessions and then having to close them out. (Admins need the View Setup and Configuration and Customize Application permissions to enable this feature.)
