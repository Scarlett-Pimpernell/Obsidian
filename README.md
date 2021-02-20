# Obsidian
Intelligent Enterprise Architecture - Human Interaction Interface, Search Engine, Artificial Intelligence Agent, and M-Graph Database.

Current Development Focus Is On the Core Search Engine Algorithm. I haven't thoroughly tested the queries yet, so be aware that there may be minor bugs. Also, I am now well advanced in coding v01.04, which includes the ability to understand relationships within the text of a given document. Unfortunately, once again, may have to wait a while for this one, as I need to upgrade my hardware in order to continue... also dealing with an extremely complex technique which will most probably take a few weeks to get right at current rates of development.

The latest upload includes a technique for fragment purposym and semantic associate matching within the search engine algorithm. Run the appropriate queries on your SQL Server 2017/2019 database, using either SSMS or Visual Studio 2017/2019. Set-up steps include: 1.Execute the MS_Text_Search_Purposym_And_Semantic_Associate_Thesauruses_Integration_T-SQL_SQL_Server_2019_IOC_v01.03.13_MAJOR.txt query (once you have sourced a representative set of important enterprise Text files and/or Microsoft Word documents); 2.Finally execute the MS_Text_Search_Technique_T-SQL_SQL_Server_2019_IOC_v01.03.02_MAJOR.txt query. The results should display in the appropriate panel. If you're feeling brave, consider integrating these steps into your existing or new product/service/experience, but bare in mind that there will be incremental changes going forward.

Over the coming weeks and months, I will gradually add to the back-end, API gateway, and front-end code, with the aim of producing an open-source high-performance (effective and efficient), feautre-rich library of configure and integrate code, in order for companies of any size to optimally plan, transform, and run their organisation via a robust enterprise architecture digital twin paradigm.

I won't be dealing with parameter binding, indexes, or query execution plans until much later in development, when I build the UI. 

Upon further reflection, I believe that the SQL injection and Powershell injection vulnerabilities which exist whenever you use dynamic SQL in a query, have not been suitably fixed by default within SQL Server 2019. The hacker who has public access to the code could simply insert whetever SQL or Powershell they wanted into the filenames that are extracted and used in the query, along with clever use of apostrophes (you may have to use new line or carriage return characters, as well, with some coding languages). I think Micrsoft may have to do something about this vulnerability, but for now the manual workaround (which is subject to common human-error) is to enclose every consecutive apostrophe string-pattern in single apostrophes, using a replace function around the @Variable in each dynamic SQL string. This encapsulation method can be applied to any computer program, algorithm, or technique which is vulnerable to code injection because it is dynamically 'structured' i.e. where variables are used in the method code, rather than only as an attribute or value to be passed to the method. Simply switch the apostrophe to its requisite string declaration character in whatever coding language you are using. If in your coding language of choice, strings are declared by a single character (i.e. without encapsulation), all you need to do to protect your code is to use a replace function on the @Variable references which adds another single string declaration character to any existing consecutive single string declaration characters within the variable. 
