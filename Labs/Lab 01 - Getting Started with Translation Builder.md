## **Lab 01: Getting Started with Translation Builder**

**Overview**: In this lab, you will learn how to work with Translations
Builder and Power BI Desktop to build multi-language reports for Power
BI. You will start by downloading a PBIX project file named
**TB-Lab01.pbix** and opening it in Power BI Desktop. Once you have
opened **TB-Lab01.pbix,** you will launch Translations Builder and move
through the steps to add metadata translations and report label
translations. At various milestones in this lab, you will be required to
publish the **TB-Lab01.pbix** project from Power BI Desktop to the Power
BI Service so you can test how the translations you’ve added to ensure
they appear to users when loaded using different languages and different
cultures.

**Prerequisite 1**: To complete this lab, you will need a Power BI
workspace where you have appropriate permissions to publish project from
Power BI Desktop to test your work. This workspace must also be
associated with a Premium capacity as indicated by the diamond image
(*see below*) displayed after the workspace name. A workspace in a
premium capacity is required because Power BI translations do not load
properly for reports running in the shared capacity.

<img src="./images/Lab01/media/image1.png"
style="width:3.30818in;height:1.10708in" />

**Prerequisite 2**: This lab assumes you’ve already installed
Translations Builder. If you haven’t installed Translations Builder yet,
you must follow steps in the [Translations Builder Installation
Guide](https://github.com/PowerBiDevCamp/TranslationsBuilder/blob/main/Docs/Installation%20Guide.md)
before continuing with these lab exercises.

### Exercise 1: Creating and Testing Metadata Translations

In this exercise, you will begin by downloading a PBIX file which
already has a simple data model and a single page report. You will then
publish the project to the Power BI Service to set up a process whereby
you can test out how your translations appear to report consumers.

1.  Download the PBIX starter file named **TB-Lab01.pbix** from the
    following link

<https://github.com/PowerBiDevCamp/TranslationsBuilder/raw/main/Labs/StarterFiles/TB-Lab01.pbix>

2.  Create a new folder on your local hard drive for these lab exercises
    such as **C:\DevCampLabs\\**.

<img src="./images/Lab01/media/image2.png"
style="width:3.42767in;height:1.25421in" />

3.  Copy **TB-Lab01.pbix** into the lab folder and then open it in Power
    BI Desktop to examine the report inside.

<img src="./images/Lab01/media/image3.png"
style="width:4.28128in;height:2.39831in"
alt="Graphical user interface, application, table Description automatically generated" />

4.  While in **Report view**, examine the **Fields** list to see the
    tables, columns and measure that are not hidden.

<img src="./images/Lab01/media/image4.png"
style="width:1.4211in;height:1.77987in" />

5.  Now, navigate to **Model view** so you can see the entire data model
    including the columns hidden from **Report view**.

<img src="./images/Lab01/media/image5.png"
style="width:3.65079in;height:2.39214in" />

6.  Navigate to Data view and examine the rows of the **Products**
    table.

<img src="./images/Lab01/media/image6.png"
style="width:3.98413in;height:2.40207in" />

Now you are going to publish the **TB-Lab01.pbix** project to a
workspace in the Power BI Service.

7.  Navigate to the **Home** tab and then click the **Publish** button.

<img src="./images/Lab01/media/image7.png"
style="width:5.61275in;height:1.11111in" />

8.  When prompted by the **Publish to Power BI** dialog, choose your
    test workspace and then click **Select**.

<img src="./images/Lab01/media/image8.png"
style="width:2.86537in;height:1.57233in" />

9.  Once you see **Success!**, click **Open ‘TB-Lab01.pbx’ in Power BI**
    to view the report in the Power BI Service.

<img src="./images/Lab01/media/image9.png"
style="width:2.83648in;height:1.69537in" />

10. The report named **TB-Lab01** should appear like the report in the
    screenshot below.

<img src="./images/Lab01/media/image10.png"
style="width:5.23747in;height:2.88679in" />

Now it’s time to begin adding translations. As you begin to add
translations to a PBIX project, you will often follow this set of
steps:  
**(1)** make changes in Power BI Desktop, **(2)** publish the project,
**(3)** check your work in the Power BI Service, **(4)** repeat until
happy

11. Return to Power BI Desktop, navigate to the **External Tools** tab
    and launch **Translations Builder**.

<img src="./images/Lab01/media/image11.png"
style="width:5.20002in;height:1.38298in" />

12. Translations Builder should start and load the data model for
    **TB-Lab01.pbix** as shown in the following screenshot.

<img src="./images/Lab01/media/image12.png"
style="width:4.2747in;height:2.09975in"
alt="Graphical user interface, application Description automatically generated" />

13. The **Dataset properties** section provides details about the
    dataset connection and the PBIX project file.

<img src="./images/Lab01/media/image13.png"
style="width:2.08176in;height:1.00559in" />

14. The grid on the bottom of the page displays one row for each
    non-hidden dataset object in the data model.

<img src="./images/Lab01/media/image14.png"
style="width:3.04403in;height:1.18999in" />

Tables, columns and measures that are hidden from report view in the
data model are not displayed. You don’t need to translate them.

15. Click the **Add Language** button to add your first secondary
    language.

<img src="./images/Lab01/media/image15.png"
style="width:5.07727in;height:0.85714in" />

16. Select **Spanish \[es-ES\]** and click **Add Language**.

<img src="./images/Lab01/media/image16.png"
style="width:2.05489in;height:2.15426in" />

17. You should now see that **Spanish \[es-ES\]** appears the first
    language in the **Secondary Languages** list.

<img src="./images/Lab01/media/image17.png"
style="width:5.20495in;height:1.22222in" />

18. You will also notice that a new column has been added for Spanish
    translations.

<img src="./images/Lab01/media/image18.png"
style="width:4.63759in;height:1.61905in" />

19. Locate the row for the **Products** table and click on the cell for
    the **Spanish** column. It should turn blue when selected.

<img src="./images/Lab01/media/image19.png"
style="width:4.50937in;height:0.90476in" />

20. Type Hello World. You should see that you can just start typing in
    the selected cell to add or edit a translation.

<img src="./images/Lab01/media/image20.png"
style="width:4.48425in;height:0.88889in" />

21. Press the **ENTER** key to save your changes. Note that pressing
    **ENTER** will move the selection to the cell below.

<img src="./images/Lab01/media/image21.png"
style="width:4.48403in;height:0.85984in" />

22. Now, type more text and press **ENTER** repeatedly to experiment
    quickly adding text to all cells in the Spanish column.

<img src="./images/Lab01/media/image22.png"
style="width:4.3493in;height:1.34921in" />

The point of the last few steps has been for you to become comfortable
with the translation editing experience. You can see the grid provides
an editing experience similar to working with Excel. You can even use
the **{F2}** key to move a cell with content into edit mode.

23. Now edit the translations in the Spanish columns with better
    translated values. Use the following translations.

24. For the **Products** table, enter the Spanish translation of
    **Productos**.

25. For the **Product** column, enter the Spanish translation of
    **Producto**

26. For the **Image** column, enter the Spanish translation of
    **Imagen**.

27. For the **Sales** table, enter the Spanish translation of
    **Ventas**.

28. For the **Sales Revenue** measure, enter the Spanish translation of
    **Ingresos Por Ventas**.

29. For the **Units Sold** measure, enter the Spanish translation of
    **Unidades Vendidas**.

30. When you are done with your edits, the Spanish translations should
    match the following screenshot.

<img src="./images/Lab01/media/image23.png"
style="width:3.8239in;height:1.22098in" />

31. Return to the **TB-Lab01.pbix** project in Power BI Desktop and save
    your work by clicking the **Save** button.

<img src="./images/Lab01/media/image24.png"
style="width:3.19497in;height:0.947in" />

It’s easy to forget to save your changes in Power BI Desktop. Be aware
that any changes made by Translations Builder are just made to the data
model loaded in memory. None of your changes are saved back to the PBIX
project file until you save in Power BI Desktop.

32. Publish the **TB-Lab01.pbix** project to push the changes to the
    project’s translations to the Power BI Service.

<img src="./images/Lab01/media/image25.png"
style="width:5.19816in;height:0.8239in" />

33. When prompted by the **Replace this dataset?** Dialog, click the
    **Replace** button to continue.

<img src="./images/Lab01/media/image26.png"
style="width:2.17282in;height:1.41509in" />

34. Once you see **Success!**, click **Open ‘TB-Lab01.pbx’ in Power BI**
    to view the report in the Power BI Service.

<img src="./images/Lab01/media/image27.png"
style="width:2.11831in;height:1.3231in"
alt="Graphical user interface, text, application, email Description automatically generated" />

35. The report should load as normal showing all text in English at
    first.

<img src="./images/Lab01/media/image28.png"
style="width:4.3122in;height:2.71669in"
alt="Table Description automatically generated" />

36. Inspect the table visual column headers which displays the names of
    columns and measures in English.

<img src="./images/Lab01/media/image29.png"
style="width:4.36478in;height:1.3105in" />

Now, it’s time to test your translations for the first time by using the
**language** query string parameter to load the report.

Click the browser address bar and add the following **language**
parameter to the end of the report URL.

/?language=es-ES

37. Press **ENTER.** You should see the **language** query string
    parameter accepted by the browser as it reloads the report.

<img src="./images/Lab01/media/image30.png"
style="width:6.48154in;height:0.81132in" />

When the report reloads, you should see the UI experience for the Power
BI Service UI switch from English to Spanish.

38. Verify the column and measure names in columns headings are
    displayed with the Spanish translations you added.

<img src="./images/Lab01/media/image31.png"
style="width:5.50275in;height:1.49685in" />

You have now successfully added the metadata translations to display
this report in both English and Spanish. Leave Power BI Desktop and
Translations Builder open as you will continue using them in your next
exercise.

### Exercise 2: Generating Machine Translations

In this lab you will configure Translations Builder’s support to
automatically generate machine translations using the Azure Translator
Service. While machine translations might not prove good enough to use
in all production scenarios, they do provide a great first step in
generating translations for testing and getting something into
production sooner.

To complete this lab you will require a **Key** and **Location** which
provide access to the **Azure Translator Service**. If you do not have a
Azure subscription and you cannot obtain your own Key, you can use the
following Key and Location up through February 28, 2023.

**Key**: a75b371ce1fc402ca84a05732cfcff27

**Location**: eastus2

1.  Return to Translations Builder and drop down the **Dataset
    Connection** menu.

<img src="./images/Lab01/media/image32.png"
style="width:3.25397in;height:1.03885in" />

39. Select the **Configure Settings…** menu command to display the
    **Configuration Options** dialog.

<img src="./images/Lab01/media/image33.png"
style="width:4.00833in;height:1.60606in" />

40. In the **Configuration Options** dialog, enter the **Key** and
    **Location** for the Azure Translator Service.

<img src="./images/Lab01/media/image34.png"
style="width:4.05319in;height:1.90012in" />

41. Once you have added the **Key** and **Location**, click **Save
    Changes**.

<img src="./images/Lab01/media/image35.png"
style="width:4.62372in;height:1.74468in" />

42. After you have configured the **Key** and **Location** for the Azure
    Translator Service, new controls will appear on the main page.

<img src="./images/Lab01/media/image36.png"
style="width:5.88222in;height:1.57143in" />

Now that you have added support for generating machine translations,
it’s time to put that automatic translation support to work!

43. Click the **Add Language** button to add your second secondary
    language.

<img src="./images/Lab01/media/image37.png"
style="width:5.60569in;height:1.26984in" />

You can hold down the **CTRL** key in the **Add Language** dialog while
selecting languages to enable multiple selection

44. Hold down the **CTRL**, and select **Dutch**, **French**, **German**
    and **Italian**. And then click **Add Language**.

<img src="./images/Lab01/media/image38.png"
style="width:1.88889in;height:1.98023in" />

45. You should now see that all four new languages appear as second
    languages in the **Secondary Languages** list.

46. You will also notice that new columns have been added to the
    translation grid for each new language.

<img src="./images/Lab01/media/image39.png"
style="width:6.65011in;height:2.35051in" />

47. In the **Machine Translations – Single Language** section, select
    **French \[fr-FR\]** from the drop down menu.

<img src="./images/Lab01/media/image40.png"
style="width:5.1117in;height:1.10646in" />

48. Once you have selected **French \[fr-FR\]**, click **Generate
    Translations** to create French translations for all rows in the
    grid.

<img src="./images/Lab01/media/image41.png"
style="width:5.15957in;height:1.18663in" />

49. As the code runs to interact with the Azure Translator Service, the
    **Generating machine translation** dialog shows the progress.

<img src="./images/Lab01/media/image42.png"
style="width:5.07042in;height:1.92598in" />

50. Once this dialog closes, you should see all cells the French column
    has been filled with machine generated translations.

<img src="./images/Lab01/media/image43.png"
style="width:6.23793in;height:1.78236in" />

51. Click the **Fill All Empty Translation** button in the **Machine
    Translations - All Languages** section.

<img src="./images/Lab01/media/image44.png"
style="width:6.33905in;height:1.45789in" />

52. You should see that all the cells the all languages have now been
    populated with machine-generated translations.

<img src="./images/Lab01/media/image45.png"
style="width:7.48958in;height:2.91458in" />

Now, it’s time once again to test your work in the Power BI Service,

53. Return to the **TB-Lab01.pbix** project in Power BI Desktop and save
    your work by clicking the **Save** button.

<img src="./images/Lab01/media/image24.png"
style="width:3.19497in;height:0.947in"
alt="Graphical user interface, application, Word Description automatically generated" />

Don’t forget to save your work! Did we mention it’s easy to forget.

54. Publish the **TB-Lab01.pbix** project to push your changes to the
    project’s translations to the Power BI Service.

<img src="./images/Lab01/media/image25.png"
style="width:5.19816in;height:0.8239in"
alt="Graphical user interface, application Description automatically generated" />

55. When prompted by the **Replace this dataset?** Dialog, click the
    **Replace** button to continue.

<img src="./images/Lab01/media/image26.png"
style="width:1.79787in;height:1.1709in"
alt="Graphical user interface, text, application, email Description automatically generated" />

56. Once you see **Success!**, click **Open ‘TB-Lab01.pbx’ in Power BI**
    to view the report in the Power BI Service.

<img src="./images/Lab01/media/image27.png"
style="width:1.93535in;height:1.20882in"
alt="Graphical user interface, text, application, email Description automatically generated" />

57. The report should load as normal showing all text in English at
    first.

<img src="./images/Lab01/media/image28.png"
style="width:3.03299in;height:1.91078in"
alt="Table Description automatically generated" />

Now, it’s time to test your French, German, Dutch & Italian translations
using the **language** query string parameter to load the report.

58. Click the browser address bar and add the **language** parameter
    value of **fr-FR** for French to the end of the report URL.

/?language=fr-FR

59. When the report reloads, you should see the UI experience for the
    Power BI Service UI switch from English to French.

<img src="./images/Lab01/media/image46.png"
style="width:5.37121in;height:0.96133in" />

60. Verify the column and measure names in columns headings of the table
    visual are displayed with French translations.

<img src="./images/Lab01/media/image47.png"
style="width:3.71429in;height:1.0541in" />

Now that you have tested the French translations, it’s time to test the
three other new languages.

61. Click the browser address bar and add the **language** parameter
    value of **de-DE** for German to the end of the report URL.

/?language=de-DE

62. When the report reloads, you should see the UI experience for the
    Power BI Service UI switch to German.

<img src="./images/Lab01/media/image48.png"
style="width:5.68939in;height:1.00565in" />

63. Verify the column and measure names in columns headings are
    displayed with the German translations.

<img src="./images/Lab01/media/image49.png"
style="width:3.96825in;height:1.11846in" />

64. Click the browser address bar and add the **language** parameter
    value of **n-NL** for Dutch to the end of the report URL.

/?language=nl-NL

65. When the report reloads, you should see the UI experience for the
    Power BI Service UI switch to Dutch.

<img src="./images/Lab01/media/image50.png"
style="width:5.61644in;height:0.92063in" />

66. Verify the column and measure names in columns headings are
    displayed with the Dutch translations.

<img src="./images/Lab01/media/image51.png"
style="width:5.13755in;height:1.38095in" />

67. Click the browser address bar and add the **language** parameter of
    **it-IT** for Italian to the end of the report URL.

/?language=it-IT

68. When the report reloads, you should see the UI experience for the
    Power BI Service UI switch to Italian.

<img src="./images/Lab01/media/image52.png"
style="width:5.39683in;height:0.86563in" />

69. Verify the column and measure names in columns headings are
    displayed with the Italian translations.

<img src="./images/Lab01/media/image53.png"
style="width:4.92721in;height:1.30159in" />

You have now successfully added the metadata translations to display
this report in six different languages. Throughout these lab exercises,
you will continue to test all six languages in the browser as you add
additional translation support.

70. As a final step in this exercise, add a browser bookmark with a
    language parameter at the end of the for each language.

<img src="./images/Lab01/media/image54.png"
style="width:6.74489in;height:1.15873in" />

Creating a browser bookmark for each language might take a minute or two
to set up at first. However, it will save lots of time in the long run
as you continue to test the translations for this report in the lab work
that remains ahead.

### Exercise 3: Creating and Testing Report Label Translations

In this exercise, blah blah blah

1.  Rub your belly

<!-- -->

71. Tap your forehead

### Exercise 4: Creating a Workflow Process To Gather & Integrate Human Translations

In this exercise, blah blah blah

1.  Rub your belly

<!-- -->

72. Tap your forehead
