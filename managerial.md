<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <title>Три колонки с переключением</title>
  <style>
    :root {
      --accent: #0f62fe;
      --bg: #f7f9fc;
      --card: #ffffff;
    }

    * {
      box-sizing: border-box;
    }

    body {
      font-family: Inter, system-ui, Arial, sans-serif;
      background: var(--bg);
      color: #102a43;
      margin: 0;
      padding: 32px;
    }

    .page {
      max-width: 80%;
      margin: 0 auto;
    }

    .container {
      display: flex;
      gap: 20px;
      height: 620px;
      margin-top: 20px;
    }

    .column {
      flex: 1;
      padding: 18px;
      overflow-y: auto;
      border-radius: 10px;
      background: var(--card);
      box-shadow: 0 4px 14px rgba(20, 30, 40, 0.04);
      transition: flex 0.3s ease;
      cursor: pointer;
      border: 1px solid transparent;
    }

    .column:hover {
      border-color: rgba(15, 98, 254, 0.16);
    }

    /* Начальные ширины: первая колонка — широкая (70%), остальные — узкие (15% каждая) */
    .column:nth-child(1) { flex: 7.5; }
    .column:nth-child(2) { flex: 1.5; }
    .column:nth-child(3) { flex: 1.5; }

    /* При фокусе колонка становится широкой */
    .column:focus-within {
      flex: 7.5 !important;
      border-color: var(--accent);
    }

    /* Остальные колонки при фокусе — узкие */
    .column:not(:focus-within) {
      flex: 1.5 !important;
      border-color: rgb(187, 190, 201);
      background-color: rgb(233, 234, 238);
    }

    h2 {
      margin: 0 0 8px 0;
      font-size: 1rem;
      color: #102a43;
    }

    p {
      line-height: 1.6;
      color: #486581;
      margin: 0 0 12px 0;
    }

    /* Для доступности */
    .column:focus {
      outline: 2px solid var(--accent);
      outline-offset: -2px;
    }
  </style>
</head>
<body>
  <div class="page">
    <div class="container">
      <div class="column" tabindex="0" autofocus>
        <h3>How COVID-19 changed sustainable development growth strategies for companies internationally. Case study of Volkswagen AG.</h3>
        <p><strong>Abstract</strong></p>
        <p>The United Nations 2030 Agenda has set out a comprehensive and extremely relevant target, manifested in 17 Sustainable Development Goals. The COVID-19 pandemic emerged as a serious obstacle for achievement of SDGs on many levels. Years of efforts were canceled or reverted in different areas of the world, as the pandemic killed millions, increased poverty, disrupted trade, fueled unemployment. Therefore, there is a pressing need to analyze the extent of the impact that unfolded from the pandemic on each Sustainable Development Goal that is relevant to the business sector, so that the impact of the pandemic on businesses&rsquo; activity, corporate strategic planning and sustainability performance can be understood in more detail. Further progress SDG cannot be achieved on the macro level without the well-coordinated singular business performance. This enables a study about COVID-19&rsquo;s influence on corporate SDG strategy to be of high scientific relevance.</p>
        <p>For this study qualitative methodology was used. Literature analysis was conducted: among studied literature were quantitative statistical studies, qualitative interviews of CEOs. Furthermore, a case study was conducted. This study consists of theoretical and empirical parts. In the theoretical part, this paper explores general underlying features of post-covid business environment, the degree of influence of covid-19 pandemic to the current SDG performance of the business sector and of the automotive industry in particular. On top of that, possible implications of said influence for future corporate performance regarding the Sustainable Development Growth were stated. Illustration of the theoretical outtakes was attempted through a case study of Volkswagen group.</p>
        <p>The results were as such: companies worldwide, and Volkswagen group in particular, are more likely to focus attention to sustainability, to address state regulations on SDG-related topics, to address the post-covid state of social responsibility before employees, put more attention to macroeconomic forecasting, to innovate logistics and R&amp;D, to promote employees&rsquo; healthcare and to emphasize climate change pledges.</p>
        <p><strong>Part 1: Theoretical study</strong></p>
        <p>COVID-19 pandemic presented a substantial change to the business environment itself.</p>
        <p>2 major trends were noted in literature following the pandemic. Those trends represented a global paradigm change for business: the sustainability shift and return of big government.</p>
        <p>&nbsp;</p>
        <p>Before Covid-19, companies were setting increasingly ambitious targets to reduce emissions and clean up their supply chains. The economic shock that the pandemic triggered could have derailed such plans, however the opposite happened. &ldquo;Clean growth&rdquo;, and a drive for sustainable and resilient sourcing, became the new stated economic paradigm, impacting all sectors of the economy, from consumer goods to energy, agriculture and financial services.</p>
        <p>The pandemic created supply shocks. Bare supermarket shelves and global shortages of personal protective equipment (PPE) reinforced the need for companies and governments to build greater resilience against unpredicted external events. The pandemic exposed fragilities in the just-in-time supply chains that industries, including agriculture and retail, had been depending on, as well as the risks of relying on single nations as sources of traded goods.</p>
        <p>Demand change emerged due to COVID. For several years, consumers have been growing increasingly conscious of the environmental and social consequences of</p>
        <p>fast fashion, long-haul holidays and reliance on imported products. This may cause global producers to change their supply to a more sustainable, regional local basis, i.e. move them closer to the consumer. Near sourcing enables companies to be more resilient, independent from external shocks, and more sustainable, which makes it an attractive strategic choice.</p>
        <p>As markets slumped in 2020, firms with higher environmental, social and</p>
        <p>governance (ESG) ratings outperformed their peers.&nbsp; Companies worldwide see more sustainable companies as more reliable and stable in the long run, keeping in mind possible future disruptions, shocks, non-replenishable resources shortages as well as climate change.</p>
        <p>Thus, it is possible to state a shift in business paradigm towards sustainability-based thinking. Companies take more merit in sustainability and are more likely to develop more nuanced sustainability and SDG strategies.</p>
        <p>The second factor influencing the core of businesses&rsquo; SDG-based decision-making is the increasing role of state industry regulation. During the early stages of the COVID 19 crisis, governments implemented broad measures to extend support to firms and workers to preserve solvency and prevent unemployment.&nbsp; States impose more regulations (see chart 1), and its role in the economy is high. The role of the state in fostering SDGs is also quite high. So the companies are likely to address the role of the state in their SDG strategies.</p>
        <p>Theoretical lookout of COVID-19 impact on the business environment through SDG framework can help to understand how recent changes could impact businesses&rsquo; SDG strategies. COVID-19 pandemic heavily complicated the prospects of achieving SDGs by 2030. It projected adverse influence towards almost all SDGs. Progress and achievements in many spheres was reversed, including business. In this chapter the impact of COVID-19 pandemic towards the global business sphere will be explored through the SDG framework.</p>
        <p><strong>GOAL 8 Decent work and economic growth</strong></p>
        <p>This goal is set to promote sustained, inclusive and sustainable economic growth, full and productive employment and decent work for all.</p>
        <p>The COVID-19 crisis disrupted economic activities around the world and caused the worst recession since the Great Depression. By 2020, the global unemployment rate reached 6.5 per cent, up 1.1 percentage points from the previous year. The number of people unemployed worldwide increased by 33 million, reaching 220 million. Due to lockdowns millions of buyers abstained from buying, leading to a demand crash. An unfathomable amount of people couldn&rsquo;t access their workplace, millions lost jobs. During the pandemic many businesses in a wide range of economic sectors had to partially or fully re-invent their labor policies to prevent workplace dismissal, re-structure operations, and introduce digital training, with 76% of OECD and EU countries moving training online. COVID substantially raised the significance of the topic of social responsibility before the employees. In some countries like the US or countries of the EU, the state played a crucial role in containing unemployment and fostering said responsibility measures by providing subsidies to businesses, and financial support for people to ease the demand strain.&nbsp;</p>
        <p>With the roll-out of COVID-19 vaccines and continued fiscal and monetary support, the United States of America and China are expected to experience strong economic growth in 2021. However, for many other countries, economic growth will remain below pre-pandemic trends for a prolonged period (see chart 1). Companies worldwide will have to assess future economic growth of their markets.</p>
        <p>Therefore, addressing Goal 8 in new SDG strategies companies may establish measures to confront unemployment by supporting employees in cases similar to COVID, state the social responsibility before employees and strategically forecast the post-covid macroeconomic conditions in the market of operation.</p>
        <p><strong>GOAL 9 Industry, innovation and infrastructure</strong></p>
        <p>Build resilient infrastructure, promote inclusive and sustainable industrialization and foster innovation.</p>
        <p>When the COVID pandemic struck, the movement of people and goods was restricted, disrupting global value chains, as well as the global manufacturing and transport industries. Small-scale industries in particular have been severely affected. The lack of resilient infrastructure, information and communication technologies, and basic services limits the ability to perform and adjust to shocks.</p>
        <p>COVID-19 is disrupting distribution on a global scale. Increased border controls and customs regulations result in longer wait times, and lack of capacity for long-haul transportation routes create extreme challenges for the economies worldwide. Supply chain disruptions have become the most dangerous risk for companies, as evident from McKinsey report.&nbsp; Some 59% of companies say they have adopted new supply-chain risk management practices over the past year, including diversifying to reduce over reliance on China. Many companies are accelerating digital transformation of their logistics by starting to introduce capabilities like real-time order monitoring, end-to-end inventory visibility, and super-reverse logistics experiences.</p>
        <p>As it was mentioned before, companies in many industries had to revise operations and labor, introducing digital solutions in some way or another. The crisis has shown that digitalisation can increase resilience and preserve capacity in the face of stringent restrictions to physical interaction. Special emphasis of many companies was put on the introduction of digital means to the working process, including implementation of personnel training in digital skills, improving digital presence of businesses, at the same time providing digital safety.</p>
        <p>Increase in R&amp;D investments also contributes to sustainability, as the crucial role of innovation is as evident as ever. Firms may expand the share of R&amp;D expenditure for sustainability.</p>
        <p>Therefore, addressing Goal 9 in new SDG strategies companies may state innovations or revised takes on logistics, contemplate digital transformation and overall re-shaping of operations to further support sustainability, as well as examine future R&amp;D expenditures.</p>
        <p><strong>Gender equality</strong></p>
        <p>The social and economic impacts of the COVID-19 pandemic have adversely affected progress towards gender equality. Staying relevant to business topic, many women have played a central role in the response to COVID-19, as frontline health workers, care providers, and as managers and leaders of recovery efforts. Yet they remain underrepresented in leadership positions, and their rights and priorities are often not explicitly addressed in response and recovery measures.&nbsp; The crisis presents an opportunity for firms to re-shape and rebuild systems, policies and institutions to advance gender equality.</p>
        <p><strong>Good health and well-being for all</strong></p>
        <p>The pandemic has halted or reversed progress in health and poses major threats beyond the disease itself. About 90 per cent of countries are still reporting one or more disruptions to essential health services, and available data from a few countries show that the pandemic has shortened life expectancy. Not surprisingly, the virus is disproportionately affecting disadvantaged groups. The pandemic has demonstrated the importance of universal health coverage and multisectoral coordination for health emergency preparedness. Moreover, to design effective pandemic policy interventions, Governments will need to improve and strengthen basic demographic and epidemiological data collection. Firms will have to put more attention to their employees&rsquo; health.</p>
        <p><strong>Climate action</strong></p>
        <p>The global production downturn following the ubiquitous lockdowns caused a temporary dip in emissions. However, concentrations of greenhouse gasses continued to increase in 2020, reaching new record highs. Seeming more urgent and dangerous than climate change, COVID has set climate policy aside. But those problems are equally important for humanity. The climate issue is now often overlooked, but still has to be addressed. In this difficult period companies have to face the challenges presented by climate change and continue to comply with carbon neutrality goals, decreasing the rates of emissions and pollution, use of water and electricity.</p>
        <p>Thus, from evaluating the impact of COVID on the overall business environment we can state that there has been a strong change in externalities all over the world. Companies worldwide should re-evaluate their SDG tracks for them to stay relevant and be impactful in the long run.</p>
        <p><strong>Conclusion</strong><br /> As a conclusion of the theoretical part of the study, we can draft a list of the theoretical outtakes, which consists of possible changes in corporate SDG strategies or sustainability strategies. It looks like this:</p>
        <ol>
        <li>more attention to sustainability overall</li>
        <li>addressing the state regulations</li>
        <li>addressing the post-covid state of Decent work and economic growth (new labor policies)</li>
        <li>addressing the post-covid state of Industry, innovation and infrastructure (Supply-chain policy change, digitalization, R&amp;D)</li>
        <li>addressing the post-covid state of Gender equality</li>
        <li>addressing the post-covid state of Good health and well-being for all</li>
        <li>addressing the post-covid state of Climate action</li>
        </ol>
      </div>

      <div class="column" tabindex="0">
        <h3>Comparing Three Corporate Governance Indexes: Understanding Their Advantages and Disadvantages</h3>
        <p>&nbsp;</p>
        <p>Corporate governance indices (CG indices) are designed to measure the quality of corporate governance practices within an organization or within a nation. The main purpose of CG indices is to provide investors and stakeholders with an objective assessment of how well a company is governed and managed or, correspondingly, how well-off companies are in a particular country context. For this work I addressed the recommended literature . The authors of the paper developed three corporate governance indices that reflect the quality of national laws aimed at protecting corporate shareholders from being expropriated by management, minority shareholders from being expropriated by large blockholder, and creditors from being expropriated by shareholders. A review of these three indices will be presented below.</p>
        <p>Corporate Governance Index 1 measures the extent of shareholders safety against managers discretion in a given national law system. Regulatory provisions like voting rules and requirements on the board&rsquo;s composition are the first thing to look for when determining shareholders rights protection in a given national legislation. The less restrictions on voting power of shareholders (e.g. labor director appointment) the more are the rights of shareholders are protected. Restrictions on cross-shareholdings (owning of subsidiary&rsquo;s shares) improves shareholders rights, because shares of the subsidiary are usually in a greater degree under control of management. To ensure the fair participation, shareholder should be able to vote distantly, e.g. by mail, and restrictions on the length of managerial contracts are key to ensure that inefficient representatives are interchanged.</p>
        <p>The right for corporate decision is measured accordingly: for atomistic shareholders the protection can be improved by establishing rights to approve the adoption of anti-takeover measures, and rights to call for an extraordinary general meeting. For blockholders it is the ban of voting caps, that can ensure their power. The limitation here is possible conflict between blockholder interest and minority shareholders&rsquo; rights. The stated measures contradict each other. Independence of the board from managers and firm transparency are key. They are measured by lack of CEO duality and, for 2 tier systems no overlap of management and supervisory boards. Transparency of the firm, i.e. disclosure requirements, ensures that the actions of management are closely monitored, therefore creating less initiative for the management to act in self-serving interest.</p>
        <p>If a firm has high governance concentration, majority shareholder can use its power to influence the managerial decisions to their advantage at the expense of minority shareholders. Corporate governance index 2 measures the extent of regulations that increases the relative power of minority shareholders and reduces the possibility of controlling blockholder taking unfair advantage of their power. Appointment rights to minority shareholders, e.g. a right for minority shareholders to appoint an independent representative to the board of directors allows to monitor potential misuse of power by the blockholder. In this context, another beneficial stipulation is a ban of dual-class shares, so that there are no non-voting rights shares to decrease the power of minority shareholders. Decision rights are measured by the requirement for supermajority confirmation of some most important decisions in the company and the right to order an extraordinary meeting, if a certain amount of minority shareholders demand it. The lower the percentage of shareholders required to call the meeting, the more power they have.</p>
        <p>To measure the fairness of enter-exit rights for minority shareholders, authors check for following provisions: mandatory bid and fair entry right. Mandatory bid is the requirement for a shareholder that acquired a certain percentage of shares to offer the possibility for the rest of shareholders to sell their shares to this new major shareholder at a fair price. The reason being, when the control is being transferred, the share price of the company might fall, and thus the interest of the minority shareholders is affected. With this rule, minor shareholders can exit at a fair price. Fair entry right is measured by the degree of transparency of the shareholders, especially the major ones, e.g. disclosure of voting and share blocks.</p>
        <p>Corporate governance index 3 measures the extent of creditor rights protection, namely the ability of the creditor to get repayment more easily, get collateral more easily, or overtake the firm in case of insolvency. Index is compiled by analyzing the national laws on bankruptcy and reorganization, according to the ease of initiating insolvency procedure and the time and bureaucracy required to claim the assets of the bankrupt firm as a creditor. Restructuring is, conversely, a debtor-oriented measure.</p>
        <p>In conclusion, all three indices have advantages and disadvantages. All three precisely measure the country&rsquo;s extent of corporate governance quality in three separate contexts based on its institutional environment. Division to three separate models solves the problem of conflicting interests within the broad area of corporate governance &ndash; therefore making the index more practical to apply in business decision-making and more informative about the degree of protection of certain interest groups against various kinds of self-serving behavior from their counterparts inside the business structure. However, in this contextual distinction lies the most obvious disadvantage, the model created by the authors of the study is not universal. Using three indices instead of one makes assessment of corporate governance quality more complex and nuanced. Nevertheless, investors and stakeholders should take these into account when making their decisions.</p>
            </div>

      <div class="column" tabindex="0">
        <h3>The influence of Board of directors&rsquo; characteristics on company&rsquo;s performance. Case of Russia.</h3>
            <p><strong>Goals of the study</strong></p>
            <p>This study is aimed at exploring the relation between board of directors&rsquo; characteristics and firm&rsquo;s performance first theoretically through agency theory, then quantitatively by estimating correlation between two sets of data: one related to company&rsquo;s financial performance, the other encompassing characteristics of board of directors. We will examine a dataset of a number of companies listed on the Moscow stock exchange in 2018, when stock market in Russia was relatively stable.</p>
            <p><strong>Agency theory</strong></p>
            <p>Agency theory looks into the issues and solutions that arise when tasks are delegated from principals to agents in the context of competing interests. It examines the circumstances under which various types of incentive instruments and monitoring arrangements can be used to minimize welfare loss, beginning with clear assumptions about rationality, contracting, and informational conditions.</p>
            <p>In terms of CG, it relates to a specific type of agency relationship that exists between the shareholders and directors/management of a company. The shareholders, true owners of the corporation, as principals, elect the executives to act and take decisions on their behalf. The aim is to represent the views of the owners and conduct operations in their interest. Despite this clear rationale for electing the board of directors, there are a lot of instances when complicated issues come up and the executives, knowingly or unknowingly, take decisions that do not reflect shareholders&rsquo; best interest. We will try to explore this issue by examining the relation between board characteristics and performance of the company.</p>
            <p><strong>Methodology</strong></p>
            <p>Qualitative methods such as surveys, interviews, or case studies may be used to assess the impact of a particular corporate governance measure. Quantitative methods such as financial ratios and linear regression are used more frequently. This methodology will be explored in this study. To estimate correlation between performance proxy variable and each board characteristic variable we will use regression analysis. Two hypotheses on influence of each board characteristic to company&rsquo;s performance will be tested.</p>
            <p><strong>Independent variables: Board of directors&rsquo; size</strong></p>
            <p>Agency theory is a framework that explains how the interests of shareholders and managers may diverge, leading to conflicts of interest. In this context, the board of directors serves as a critical intermediary between shareholders and managers, tasked with monitoring the actions of the management team and ensuring that the company is operating in the best interests of shareholders. We chose board of directors&rsquo; size as a variable in our study, because our literary research&rsquo;s results suggested that from an agency theory standpoint, increasing the size of the board of directors can have several benefits for a company's performance. Here are a few potential advantages:</p>
            <p>More diverse perspectives: A larger board of directors can bring a wider range of skills, experiences, and perspectives to the table. This can be especially valuable in complex or rapidly changing industries, where a broad range of knowledge is essential for effective decision-making. A diverse board can also help to prevent groupthink, where members of a small, homogenous board may be more likely to agree with one another and overlook potential risks or drawbacks.</p>
            <p>Improved monitoring and oversight: With more board members, there are more eyes on the management team and more opportunities to spot potential problems or conflicts of interest. This can help to mitigate agency costs, or the expenses associated with ensuring that managers are acting in the best interests of shareholders. A larger board can also allow for more effective committees and subcommittees, which can focus on specific areas of the business and provide more in-depth oversight.</p>
            <p>Enhanced accountability: A larger board of directors can help to ensure that individual members are held accountable for their actions and decisions. With more people involved, it may be more difficult for any one member to shirk their responsibilities or avoid scrutiny. This can create a culture of accountability throughout the organization, which can ultimately lead to better performance.</p>
            <p>Of course, it's worth noting that there are potential drawbacks to increasing the size of the board of directors as well. For example, larger boards can be more difficult to coordinate and may require more time and resources to function effectively. It's also possible that larger boards could become unwieldy or bogged down in bureaucracy, which could ultimately hinder performance. Overall, however, we are going to try to suggest that there is a connection between board size and corporate governance quality, based on the abovementioned arguments.</p>
            <p>In Russia, a minimum number of directors is stipulated by law, according to the number of shareholders. For 1000 and less &ndash; 5 directors, 1000 to 10000 &ndash; 7 directors, more than 10000 &ndash; 9 directors. The maximum number of directors is not limited. We are going to analyze data only from stock companies with more than 10000 shareholders.</p>
            <p>&nbsp;</p>
            <p><strong>Independent variables: Board of directors&rsquo; independence</strong></p>
            <p>One way to mitigate the conflict between a company's management and its shareholders is by increasing the independence of the board of directors. An independent board is one that is not influenced by management, and is instead focused on representing the interests of shareholders. There are several ways in which increasing board independence can benefit a company's performance from an agency theory standpoint:</p>
            <p>Reduced agency costs: An independent board is less likely to be influenced by management, which reduces the potential for agency costs such as excessive executive compensation, poor investment decisions, and lack of accountability.</p>
            <p>Improved oversight: Independent directors can provide better oversight of management, which can help prevent or detect problems before they become serious. This can lead to better decision-making and ultimately better company performance.</p>
            <p>Enhanced shareholder trust: When shareholders see that a company has an independent board that is looking out for their interests, they are more likely to trust the company and invest in it. This can increase the company's access to capital and ultimately benefit its performance.</p>
            <p>Better alignment of incentives: Independent directors can help align the interests of management with those of shareholders by ensuring that management is held accountable for its actions and that its incentives are aligned with the company's long-term success.</p>
            <p>Overall, increasing board independence can benefit a company's performance by reducing agency costs, improving oversight, enhancing shareholder trust, and aligning incentives. These benefits can ultimately lead to better decision-making and a more successful company. Therefore, the presence of outside non-executive independent directors may increase a board&rsquo;s overall effectiveness and performance.</p>
            <ul>
            <li>An inside director is most commonly defined as a company employee, though the category sometimes also covers significant shareholders.</li>
            <li>Independent directors are only involved with the company through their board membership. Independent directors face fewer conflicts of interest than company insiders in discharging their fiduciary obligations at the same time they can bring valuable outside expertise.</li>
            </ul>
            <p>Because of this, we argue that independent directors from outside the firm may have a significant positive influence on the firm&rsquo;s value-creating activities through their strategic decision-making and neutral monitoring of management.</p>
            <p><strong>Chosen dependent variable: company&rsquo;s performance, Tobin&rsquo;s Q</strong></p>
            <p>Tobin's Q is a financial ratio that measures the market value of a company's assets relative to its replacement cost. It was introduced by economist James Tobin in 1969 as a way to evaluate a company's investment opportunities and its ability to create value for shareholders. The formula for Tobin's Q is:</p>
            <p>Tobin's Q = Market Value of Assets / Replacement Cost of Assets</p>
            <p>In general, a high Tobin's Q ratio indicates that a company's stock is undervalued and that the company has valuable investment opportunities. On the other hand, a low Tobin's Q ratio suggests that a company's stock is overvalued and that it may not have attractive investment opportunities.</p>
            <p>Many studies have found a strong correlation between Tobin's Q and a company's financial performance. For example, Singh Satwinder, Naeem Tabassum, Darwish Tamer, Batsakis Georgios) [1]. Companies with higher Tobin's Q ratios tend to have higher returns on assets, higher profit margins, and higher growth rates. In addition, companies with high Tobin's Q ratios tend to have lower levels of debt and higher levels of investment in research and development and other forms of intangible assets.</p>
            <p>One reason for the strong correlation between Tobin's Q and financial performance is that Tobin's Q is a forward-looking measure of a company's investment opportunities. Companies with high Tobin's Q ratios are seen as having more valuable investment opportunities and are therefore more likely to invest in research and development, expand their operations, and pursue other growth strategies. This can lead to higher revenue growth, higher profits, and higher returns for shareholders. Literature suggests that there is a significant correlation between Q ratio and future operating performance of the firm (Liang Fu, Rajeev Singhal, Mohinder Parkash)[2]. Therefore, Tobin&rsquo;s Q was chosen as a proxy variable for company&rsquo;s performance.</p>
      </div>
    </div>
  </div>
</body>
</html>
