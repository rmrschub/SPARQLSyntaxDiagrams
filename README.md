<a name="Query">Query:</a>
<svg xmlns="http://www.w3.org/2000/svg">
<defs>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
</defs>
</svg>
               
            PrologueSelectQueryConstructQueryDescribeQueryAskQuery



<pre><a href="#Query" title="Query">Query</a>    ::= <a href="#Prologue" title="Prologue">Prologue</a> ( <a href="#SelectQuery" title="SelectQuery">SelectQuery</a> | <a href="#ConstructQuery" title="ConstructQuery">ConstructQuery</a> | <a href="#DescribeQuery" title="DescribeQuery">DescribeQuery</a> | <a href="#AskQuery" title="AskQuery">AskQuery</a> )</pre>

no references  


<a name="Prologue">Prologue:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            BaseDeclPrefixDecl



<pre><a href="#Prologue" title="Prologue">Prologue</a> ::= <a href="#BaseDecl" title="BaseDecl">BaseDecl</a>? <a href="#PrefixDecl" title="PrefixDecl">PrefixDecl</a>*</pre>

referenced by:
         
* [Query](#Query "Query")  


<a name="BaseDecl">BaseDecl:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            BASEIRI_REF



<pre><a href="#BaseDecl" title="BaseDecl">BaseDecl</a> ::= 'BASE' <a href="#IRI_REF" title="IRI_REF">IRI_REF</a></pre>

referenced by:
         
* [Prologue](#Prologue "Prologue")  


<a name="PrefixDecl">PrefixDecl:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            PREFIXPNAME_NSIRI_REF



<pre><a href="#PrefixDecl" title="PrefixDecl">PrefixDecl</a>
         ::= 'PREFIX' <a href="#PNAME_NS" title="PNAME_NS">PNAME_NS</a><a href="#IRI_REF" title="IRI_REF">IRI_REF</a></pre>

referenced by:
         
* [Prologue](#Prologue "Prologue")  


<a name="SelectQuery">SelectQuery:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            SELECTDISTINCTREDUCEDVar*DatasetClauseWhereClauseSolutionModifier



<pre><a href="#SelectQuery" title="SelectQuery">SelectQuery</a>
         ::= 'SELECT' ( 'DISTINCT' | 'REDUCED' )? ( <a href="#Var" title="Var">Var</a>+ | '*' ) <a href="#DatasetClause" title="DatasetClause">DatasetClause</a>* <a href="#WhereClause" title="WhereClause">WhereClause</a><a href="#SolutionModifier" title="SolutionModifier">SolutionModifier</a></pre>

referenced by:
         
* [Query](#Query "Query")  


<a name="ConstructQuery">ConstructQuery:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            CONSTRUCTConstructTemplateDatasetClauseWhereClauseSolutionModifier



<pre><a href="#ConstructQuery" title="ConstructQuery">ConstructQuery</a>
         ::= 'CONSTRUCT' <a href="#ConstructTemplate" title="ConstructTemplate">ConstructTemplate</a><a href="#DatasetClause" title="DatasetClause">DatasetClause</a>* <a href="#WhereClause" title="WhereClause">WhereClause</a><a href="#SolutionModifier" title="SolutionModifier">SolutionModifier</a></pre>

referenced by:
         
* [Query](#Query "Query")  


<a name="DescribeQuery">DescribeQuery:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            DESCRIBEVarOrIRIref*DatasetClauseWhereClauseSolutionModifier



<pre><a href="#DescribeQuery" title="DescribeQuery">DescribeQuery</a>
         ::= 'DESCRIBE' ( <a href="#VarOrIRIref" title="VarOrIRIref">VarOrIRIref</a>+ | '*' ) <a href="#DatasetClause" title="DatasetClause">DatasetClause</a>* <a href="#WhereClause" title="WhereClause">WhereClause</a>? <a href="#SolutionModifier" title="SolutionModifier">SolutionModifier</a></pre>

referenced by:
         
* [Query](#Query "Query")  


<a name="AskQuery">AskQuery:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            ASKDatasetClauseWhereClause



<pre><a href="#AskQuery" title="AskQuery">AskQuery</a> ::= 'ASK' <a href="#DatasetClause" title="DatasetClause">DatasetClause</a>* <a href="#WhereClause" title="WhereClause">WhereClause</a></pre>

referenced by:
         
* [Query](#Query "Query")  


<a name="DatasetClause">DatasetClause:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            FROMDefaultGraphClauseNamedGraphClause



<pre><a href="#DatasetClause" title="DatasetClause">DatasetClause</a>
         ::= 'FROM' ( <a href="#DefaultGraphClause" title="DefaultGraphClause">DefaultGraphClause</a> | <a href="#NamedGraphClause" title="NamedGraphClause">NamedGraphClause</a> )</pre>

referenced by:
         
* [AskQuery](#AskQuery "AskQuery")
* [ConstructQuery](#ConstructQuery "ConstructQuery")
* [DescribeQuery](#DescribeQuery "DescribeQuery")
* [SelectQuery](#SelectQuery "SelectQuery")  


<a name="DefaultGraphClause">DefaultGraphClause:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            SourceSelector



<pre><a href="#DefaultGraphClause" title="DefaultGraphClause">DefaultGraphClause</a>
         ::= <a href="#SourceSelector" title="SourceSelector">SourceSelector</a></pre>

referenced by:
         
* [DatasetClause](#DatasetClause "DatasetClause")  


<a name="NamedGraphClause">NamedGraphClause:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            NAMEDSourceSelector



<pre><a href="#NamedGraphClause" title="NamedGraphClause">NamedGraphClause</a>
         ::= 'NAMED' <a href="#SourceSelector" title="SourceSelector">SourceSelector</a></pre>

referenced by:
         
* [DatasetClause](#DatasetClause "DatasetClause")  


<a name="SourceSelector">SourceSelector:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            IRIref



<pre><a href="#SourceSelector" title="SourceSelector">SourceSelector</a>
         ::= <a href="#IRIref" title="IRIref">IRIref</a></pre>

referenced by:
         
* [DefaultGraphClause](#DefaultGraphClause "DefaultGraphClause")
* [NamedGraphClause](#NamedGraphClause "NamedGraphClause")  


<a name="WhereClause">WhereClause:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            WHEREGroupGraphPattern



<pre><a href="#WhereClause" title="WhereClause">WhereClause</a>
         ::= 'WHERE'? <a href="#GroupGraphPattern" title="GroupGraphPattern">GroupGraphPattern</a></pre>

referenced by:
         
* [AskQuery](#AskQuery "AskQuery")
* [ConstructQuery](#ConstructQuery "ConstructQuery")
* [DescribeQuery](#DescribeQuery "DescribeQuery")
* [SelectQuery](#SelectQuery "SelectQuery")  


<a name="SolutionModifier">SolutionModifier:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            OrderClauseLimitOffsetClauses



<pre><a href="#SolutionModifier" title="SolutionModifier">SolutionModifier</a>
         ::= <a href="#OrderClause" title="OrderClause">OrderClause</a>? <a href="#LimitOffsetClauses" title="LimitOffsetClauses">LimitOffsetClauses</a>?</pre>

referenced by:
         
* [ConstructQuery](#ConstructQuery "ConstructQuery")
* [DescribeQuery](#DescribeQuery "DescribeQuery")
* [SelectQuery](#SelectQuery "SelectQuery")  


<a name="LimitOffsetClauses">LimitOffsetClauses:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            LimitClauseOffsetClauseOffsetClauseLimitClause



<pre><a href="#LimitOffsetClauses" title="LimitOffsetClauses">LimitOffsetClauses</a>
         ::= <a href="#LimitClause" title="LimitClause">LimitClause</a><a href="#OffsetClause" title="OffsetClause">OffsetClause</a>?
           | <a href="#OffsetClause" title="OffsetClause">OffsetClause</a><a href="#LimitClause" title="LimitClause">LimitClause</a>?</pre>

referenced by:
         
* [SolutionModifier](#SolutionModifier "SolutionModifier")  


<a name="OrderClause">OrderClause:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            ORDERBYOrderCondition



<pre><a href="#OrderClause" title="OrderClause">OrderClause</a>
         ::= 'ORDER' 'BY' <a href="#OrderCondition" title="OrderCondition">OrderCondition</a>+</pre>

referenced by:
         
* [SolutionModifier](#SolutionModifier "SolutionModifier")  


<a name="OrderCondition">OrderCondition:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            ASCDESCBrackettedExpressionConstraintVar



<pre><a href="#OrderCondition" title="OrderCondition">OrderCondition</a>
         ::= ( 'ASC' | 'DESC' ) <a href="#BrackettedExpression" title="BrackettedExpression">BrackettedExpression</a>
           | ( <a href="#Constraint" title="Constraint">Constraint</a> | <a href="#Var" title="Var">Var</a> )</pre>

referenced by:
         
* [OrderClause](#OrderClause "OrderClause")  


<a name="LimitClause">LimitClause:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            LIMITINTEGER



<pre><a href="#LimitClause" title="LimitClause">LimitClause</a>
         ::= 'LIMIT' <a href="#INTEGER" title="INTEGER">INTEGER</a></pre>

referenced by:
         
* [LimitOffsetClauses](#LimitOffsetClauses "LimitOffsetClauses")  


<a name="OffsetClause">OffsetClause:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            OFFSETINTEGER



<pre><a href="#OffsetClause" title="OffsetClause">OffsetClause</a>
         ::= 'OFFSET' <a href="#INTEGER" title="INTEGER">INTEGER</a></pre>

referenced by:
         
* [LimitOffsetClauses](#LimitOffsetClauses "LimitOffsetClauses")  


<a name="GroupGraphPattern">GroupGraphPattern:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            {TriplesBlock.GraphPatternNotTriplesFilter}



<pre><a href="#GroupGraphPattern" title="GroupGraphPattern">GroupGraphPattern</a>
         ::= '{' <a href="#TriplesBlock" title="TriplesBlock">TriplesBlock</a>? ( ( <a href="#GraphPatternNotTriples" title="GraphPatternNotTriples">GraphPatternNotTriples</a> | <a href="#Filter" title="Filter">Filter</a> ) '.'? <a href="#TriplesBlock" title="TriplesBlock">TriplesBlock</a>? )* '}'</pre>

referenced by:
         
* [GraphGraphPattern](#GraphGraphPattern "GraphGraphPattern")
* [GroupOrUnionGraphPattern](#GroupOrUnionGraphPattern "GroupOrUnionGraphPattern")
* [OptionalGraphPattern](#OptionalGraphPattern "OptionalGraphPattern")
* [WhereClause](#WhereClause "WhereClause")  


<a name="TriplesBlock">TriplesBlock:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            TriplesSameSubject.TriplesBlock



<pre><a href="#TriplesBlock" title="TriplesBlock">TriplesBlock</a>
         ::= <a href="#TriplesSameSubject" title="TriplesSameSubject">TriplesSameSubject</a> ( '.' <a href="#TriplesBlock" title="TriplesBlock">TriplesBlock</a>? )?</pre>

referenced by:
         
* [GroupGraphPattern](#GroupGraphPattern "GroupGraphPattern")
* [TriplesBlock](#TriplesBlock "TriplesBlock")  


<a name="GraphPatternNotTriples">GraphPatternNotTriples:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            OptionalGraphPatternGroupOrUnionGraphPatternGraphGraphPattern



<pre><a href="#GraphPatternNotTriples" title="GraphPatternNotTriples">GraphPatternNotTriples</a>
         ::= <a href="#OptionalGraphPattern" title="OptionalGraphPattern">OptionalGraphPattern</a>
           | <a href="#GroupOrUnionGraphPattern" title="GroupOrUnionGraphPattern">GroupOrUnionGraphPattern</a>
           | <a href="#GraphGraphPattern" title="GraphGraphPattern">GraphGraphPattern</a></pre>

referenced by:
         
* [GroupGraphPattern](#GroupGraphPattern "GroupGraphPattern")  


<a name="OptionalGraphPattern">OptionalGraphPattern:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            OPTIONALGroupGraphPattern



<pre><a href="#OptionalGraphPattern" title="OptionalGraphPattern">OptionalGraphPattern</a>
         ::= 'OPTIONAL' <a href="#GroupGraphPattern" title="GroupGraphPattern">GroupGraphPattern</a></pre>

referenced by:
         
* [GraphPatternNotTriples](#GraphPatternNotTriples "GraphPatternNotTriples")  


<a name="GraphGraphPattern">GraphGraphPattern:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            GRAPHVarOrIRIrefGroupGraphPattern



<pre><a href="#GraphGraphPattern" title="GraphGraphPattern">GraphGraphPattern</a>
         ::= 'GRAPH' <a href="#VarOrIRIref" title="VarOrIRIref">VarOrIRIref</a><a href="#GroupGraphPattern" title="GroupGraphPattern">GroupGraphPattern</a></pre>

referenced by:
         
* [GraphPatternNotTriples](#GraphPatternNotTriples "GraphPatternNotTriples")  


<a name="GroupOrUnionGraphPattern">GroupOrUnionGraphPattern:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            GroupGraphPatternUNION



<pre><a href="#GroupOrUnionGraphPattern" title="GroupOrUnionGraphPattern">GroupOrUnionGraphPattern</a>
         ::= <a href="#GroupGraphPattern" title="GroupGraphPattern">GroupGraphPattern</a> ( 'UNION' <a href="#GroupGraphPattern" title="GroupGraphPattern">GroupGraphPattern</a> )*</pre>

referenced by:
         
* [GraphPatternNotTriples](#GraphPatternNotTriples "GraphPatternNotTriples")  


<a name="Filter">Filter:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            FILTERConstraint



<pre><a href="#Filter" title="Filter">Filter</a>   ::= 'FILTER' <a href="#Constraint" title="Constraint">Constraint</a></pre>

referenced by:
         
* [GroupGraphPattern](#GroupGraphPattern "GroupGraphPattern")  


<a name="Constraint">Constraint:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            BrackettedExpressionBuiltInCallFunctionCall



<pre><a href="#Constraint" title="Constraint">Constraint</a>
         ::= <a href="#BrackettedExpression" title="BrackettedExpression">BrackettedExpression</a>
           | <a href="#BuiltInCall" title="BuiltInCall">BuiltInCall</a>
           | <a href="#FunctionCall" title="FunctionCall">FunctionCall</a></pre>

referenced by:
         
* [Filter](#Filter "Filter")
* [OrderCondition](#OrderCondition "OrderCondition")  


<a name="FunctionCall">FunctionCall:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            IRIrefArgList



<pre><a href="#FunctionCall" title="FunctionCall">FunctionCall</a>
         ::= <a href="#IRIref" title="IRIref">IRIref</a><a href="#ArgList" title="ArgList">ArgList</a></pre>

referenced by:
         
* [Constraint](#Constraint "Constraint")  


<a name="ArgList">ArgList:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            NIL(Expression,)



<pre><a href="#ArgList" title="ArgList">ArgList</a>  ::= <a href="#NIL" title="NIL">NIL</a>
           | '(' <a href="#Expression" title="Expression">Expression</a> ( ',' <a href="#Expression" title="Expression">Expression</a> )* ')'</pre>

referenced by:
         
* [FunctionCall](#FunctionCall "FunctionCall")
* [IRIrefOrFunction](#IRIrefOrFunction "IRIrefOrFunction")  


<a name="ConstructTemplate">ConstructTemplate:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            {ConstructTriples}



<pre><a href="#ConstructTemplate" title="ConstructTemplate">ConstructTemplate</a>
         ::= '{' <a href="#ConstructTriples" title="ConstructTriples">ConstructTriples</a>? '}'</pre>

referenced by:
         
* [ConstructQuery](#ConstructQuery "ConstructQuery")  


<a name="ConstructTriples">ConstructTriples:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            TriplesSameSubject.ConstructTriples



<pre><a href="#ConstructTriples" title="ConstructTriples">ConstructTriples</a>
         ::= <a href="#TriplesSameSubject" title="TriplesSameSubject">TriplesSameSubject</a> ( '.' <a href="#ConstructTriples" title="ConstructTriples">ConstructTriples</a>? )?</pre>

referenced by:
         
* [ConstructTemplate](#ConstructTemplate "ConstructTemplate")
* [ConstructTriples](#ConstructTriples "ConstructTriples")  


<a name="TriplesSameSubject">TriplesSameSubject:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            VarOrTermPropertyListNotEmptyTriplesNodePropertyList



<pre><a href="#TriplesSameSubject" title="TriplesSameSubject">TriplesSameSubject</a>
         ::= <a href="#VarOrTerm" title="VarOrTerm">VarOrTerm</a><a href="#PropertyListNotEmpty" title="PropertyListNotEmpty">PropertyListNotEmpty</a>
           | <a href="#TriplesNode" title="TriplesNode">TriplesNode</a><a href="#PropertyList" title="PropertyList">PropertyList</a></pre>

referenced by:
         
* [ConstructTriples](#ConstructTriples "ConstructTriples")
* [TriplesBlock](#TriplesBlock "TriplesBlock")  


<a name="PropertyListNotEmpty">PropertyListNotEmpty:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            VerbObjectList;VerbObjectList



<pre><a href="#PropertyListNotEmpty" title="PropertyListNotEmpty">PropertyListNotEmpty</a>
         ::= <a href="#Verb" title="Verb">Verb</a><a href="#ObjectList" title="ObjectList">ObjectList</a> ( ';' ( <a href="#Verb" title="Verb">Verb</a><a href="#ObjectList" title="ObjectList">ObjectList</a> )? )*</pre>

referenced by:
         
* [BlankNodePropertyList](#BlankNodePropertyList "BlankNodePropertyList")
* [PropertyList](#PropertyList "PropertyList")
* [TriplesSameSubject](#TriplesSameSubject "TriplesSameSubject")  


<a name="PropertyList">PropertyList:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            PropertyListNotEmpty



<pre><a href="#PropertyList" title="PropertyList">PropertyList</a>
         ::= <a href="#PropertyListNotEmpty" title="PropertyListNotEmpty">PropertyListNotEmpty</a>?</pre>

referenced by:
         
* [TriplesSameSubject](#TriplesSameSubject "TriplesSameSubject")  


<a name="ObjectList">ObjectList:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            Object,



<pre><a href="#ObjectList" title="ObjectList">ObjectList</a>
         ::= <a href="#Object" title="Object">Object</a> ( ',' <a href="#Object" title="Object">Object</a> )*</pre>

referenced by:
         
* [PropertyListNotEmpty](#PropertyListNotEmpty "PropertyListNotEmpty")  


<a name="Object">Object:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            GraphNode



<pre><a href="#Object" title="Object">Object</a>   ::= <a href="#GraphNode" title="GraphNode">GraphNode</a></pre>

referenced by:
         
* [ObjectList](#ObjectList "ObjectList")  


<a name="Verb">Verb:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            VarOrIRIrefa



<pre><a href="#Verb" title="Verb">Verb</a>     ::= <a href="#VarOrIRIref" title="VarOrIRIref">VarOrIRIref</a>
           | 'a'</pre>

referenced by:
         
* [PropertyListNotEmpty](#PropertyListNotEmpty "PropertyListNotEmpty")  


<a name="TriplesNode">TriplesNode:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            CollectionBlankNodePropertyList



<pre><a href="#TriplesNode" title="TriplesNode">TriplesNode</a>
         ::= <a href="#Collection" title="Collection">Collection</a>
           | <a href="#BlankNodePropertyList" title="BlankNodePropertyList">BlankNodePropertyList</a></pre>

referenced by:
         
* [GraphNode](#GraphNode "GraphNode")
* [TriplesSameSubject](#TriplesSameSubject "TriplesSameSubject")  


<a name="BlankNodePropertyList">BlankNodePropertyList:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            [PropertyListNotEmpty]



<pre><a href="#BlankNodePropertyList" title="BlankNodePropertyList">BlankNodePropertyList</a>
         ::= '[' <a href="#PropertyListNotEmpty" title="PropertyListNotEmpty">PropertyListNotEmpty</a> ']'</pre>

referenced by:
         
* [TriplesNode](#TriplesNode "TriplesNode")  


<a name="Collection">Collection:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            (GraphNode)



<pre><a href="#Collection" title="Collection">Collection</a>
         ::= '(' <a href="#GraphNode" title="GraphNode">GraphNode</a>+ ')'</pre>

referenced by:
         
* [TriplesNode](#TriplesNode "TriplesNode")  


<a name="GraphNode">GraphNode:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            VarOrTermTriplesNode



<pre><a href="#GraphNode" title="GraphNode">GraphNode</a>
         ::= <a href="#VarOrTerm" title="VarOrTerm">VarOrTerm</a>
           | <a href="#TriplesNode" title="TriplesNode">TriplesNode</a></pre>

referenced by:
         
* [Collection](#Collection "Collection")
* [Object](#Object "Object")  


<a name="VarOrTerm">VarOrTerm:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            VarGraphTerm



<pre><a href="#VarOrTerm" title="VarOrTerm">VarOrTerm</a>
         ::= <a href="#Var" title="Var">Var</a>
           | <a href="#GraphTerm" title="GraphTerm">GraphTerm</a></pre>

referenced by:
         
* [GraphNode](#GraphNode "GraphNode")
* [TriplesSameSubject](#TriplesSameSubject "TriplesSameSubject")  


<a name="VarOrIRIref">VarOrIRIref:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            VarIRIref



<pre><a href="#VarOrIRIref" title="VarOrIRIref">VarOrIRIref</a>
         ::= <a href="#Var" title="Var">Var</a>
           | <a href="#IRIref" title="IRIref">IRIref</a></pre>

referenced by:
         
* [DescribeQuery](#DescribeQuery "DescribeQuery")
* [GraphGraphPattern](#GraphGraphPattern "GraphGraphPattern")
* [Verb](#Verb "Verb")  


<a name="Var">Var:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            VAR1VAR2



<pre><a href="#Var" title="Var">Var</a>      ::= <a href="#VAR1" title="VAR1">VAR1</a>
           | <a href="#VAR2" title="VAR2">VAR2</a></pre>

referenced by:
         
* [BuiltInCall](#BuiltInCall "BuiltInCall")
* [OrderCondition](#OrderCondition "OrderCondition")
* [PrimaryExpression](#PrimaryExpression "PrimaryExpression")
* [SelectQuery](#SelectQuery "SelectQuery")
* [VarOrIRIref](#VarOrIRIref "VarOrIRIref")
* [VarOrTerm](#VarOrTerm "VarOrTerm")  


<a name="GraphTerm">GraphTerm:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            IRIrefRDFLiteralNumericLiteralBooleanLiteralBlankNodeNIL



<pre><a href="#GraphTerm" title="GraphTerm">GraphTerm</a>
         ::= <a href="#IRIref" title="IRIref">IRIref</a>
           | <a href="#RDFLiteral" title="RDFLiteral">RDFLiteral</a>
           | <a href="#NumericLiteral" title="NumericLiteral">NumericLiteral</a>
           | <a href="#BooleanLiteral" title="BooleanLiteral">BooleanLiteral</a>
           | <a href="#BlankNode" title="BlankNode">BlankNode</a>
           | <a href="#NIL" title="NIL">NIL</a></pre>

referenced by:
         
* [VarOrTerm](#VarOrTerm "VarOrTerm")  


<a name="Expression">Expression:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            ConditionalOrExpression



<pre><a href="#Expression" title="Expression">Expression</a>
         ::= <a href="#ConditionalOrExpression" title="ConditionalOrExpression">ConditionalOrExpression</a></pre>

referenced by:
         
* [ArgList](#ArgList "ArgList")
* [BrackettedExpression](#BrackettedExpression "BrackettedExpression")
* [BuiltInCall](#BuiltInCall "BuiltInCall")
* [RegexExpression](#RegexExpression "RegexExpression")  


<a name="ConditionalOrExpression">ConditionalOrExpression:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            ConditionalAndExpression||



<pre><a href="#ConditionalOrExpression" title="ConditionalOrExpression">ConditionalOrExpression</a>
         ::= <a href="#ConditionalAndExpression" title="ConditionalAndExpression">ConditionalAndExpression</a> ( '||' <a href="#ConditionalAndExpression" title="ConditionalAndExpression">ConditionalAndExpression</a> )*</pre>

referenced by:
         
* [Expression](#Expression "Expression")  


<a name="ConditionalAndExpression">ConditionalAndExpression:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            ValueLogical&&



<pre><a href="#ConditionalAndExpression" title="ConditionalAndExpression">ConditionalAndExpression</a>
         ::= <a href="#ValueLogical" title="ValueLogical">ValueLogical</a> ( '&&' <a href="#ValueLogical" title="ValueLogical">ValueLogical</a> )*</pre>

referenced by:
         
* [ConditionalOrExpression](#ConditionalOrExpression "ConditionalOrExpression")  


<a name="ValueLogical">ValueLogical:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            RelationalExpression



<pre><a href="#ValueLogical" title="ValueLogical">ValueLogical</a>
         ::= <a href="#RelationalExpression" title="RelationalExpression">RelationalExpression</a></pre>

referenced by:
         
* [ConditionalAndExpression](#ConditionalAndExpression "ConditionalAndExpression")  


<a name="RelationalExpression">RelationalExpression:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            NumericExpression=NumericExpression!=NumericExpression<NumericExpression>NumericExpression<=NumericExpression>=NumericExpression



<pre><a href="#RelationalExpression" title="RelationalExpression">RelationalExpression</a>
         ::= <a href="#NumericExpression" title="NumericExpression">NumericExpression</a> ( '=' <a href="#NumericExpression" title="NumericExpression">NumericExpression</a> | '!=' <a href="#NumericExpression" title="NumericExpression">NumericExpression</a> | '<' <a href="#NumericExpression" title="NumericExpression">NumericExpression</a> | '>' <a href="#NumericExpression" title="NumericExpression">NumericExpression</a> | '<=' <a href="#NumericExpression" title="NumericExpression">NumericExpression</a> | '>=' <a href="#NumericExpression" title="NumericExpression">NumericExpression</a> )?</pre>

referenced by:
         
* [ValueLogical](#ValueLogical "ValueLogical")  


<a name="NumericExpression">NumericExpression:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            AdditiveExpression



<pre><a href="#NumericExpression" title="NumericExpression">NumericExpression</a>
         ::= <a href="#AdditiveExpression" title="AdditiveExpression">AdditiveExpression</a></pre>

referenced by:
         
* [RelationalExpression](#RelationalExpression "RelationalExpression")  


<a name="AdditiveExpression">AdditiveExpression:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            MultiplicativeExpression+MultiplicativeExpression-MultiplicativeExpressionNumericLiteralPositiveNumericLiteralNegative



<pre><a href="#AdditiveExpression" title="AdditiveExpression">AdditiveExpression</a>
         ::= <a href="#MultiplicativeExpression" title="MultiplicativeExpression">MultiplicativeExpression</a> ( '+' <a href="#MultiplicativeExpression" title="MultiplicativeExpression">MultiplicativeExpression</a> | '-' <a href="#MultiplicativeExpression" title="MultiplicativeExpression">MultiplicativeExpression</a> | <a href="#NumericLiteralPositive" title="NumericLiteralPositive">NumericLiteralPositive</a> | <a href="#NumericLiteralNegative" title="NumericLiteralNegative">NumericLiteralNegative</a> )*</pre>

referenced by:
         
* [NumericExpression](#NumericExpression "NumericExpression")  


<a name="MultiplicativeExpression">MultiplicativeExpression:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            UnaryExpression*UnaryExpression/UnaryExpression



<pre><a href="#MultiplicativeExpression" title="MultiplicativeExpression">MultiplicativeExpression</a>
         ::= <a href="#UnaryExpression" title="UnaryExpression">UnaryExpression</a> ( '*' <a href="#UnaryExpression" title="UnaryExpression">UnaryExpression</a> | '/' <a href="#UnaryExpression" title="UnaryExpression">UnaryExpression</a> )*</pre>

referenced by:
         
* [AdditiveExpression](#AdditiveExpression "AdditiveExpression")  


<a name="UnaryExpression">UnaryExpression:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            !PrimaryExpression+PrimaryExpression-PrimaryExpressionPrimaryExpression



<pre><a href="#UnaryExpression" title="UnaryExpression">UnaryExpression</a>
         ::= '!' <a href="#PrimaryExpression" title="PrimaryExpression">PrimaryExpression</a>
           | '+' <a href="#PrimaryExpression" title="PrimaryExpression">PrimaryExpression</a>
           | '-' <a href="#PrimaryExpression" title="PrimaryExpression">PrimaryExpression</a>
           | <a href="#PrimaryExpression" title="PrimaryExpression">PrimaryExpression</a></pre>

referenced by:
         
* [MultiplicativeExpression](#MultiplicativeExpression "MultiplicativeExpression")  


<a name="PrimaryExpression">PrimaryExpression:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            BrackettedExpressionBuiltInCallIRIrefOrFunctionRDFLiteralNumericLiteralBooleanLiteralVar



<pre><a href="#PrimaryExpression" title="PrimaryExpression">PrimaryExpression</a>
         ::= <a href="#BrackettedExpression" title="BrackettedExpression">BrackettedExpression</a>
           | <a href="#BuiltInCall" title="BuiltInCall">BuiltInCall</a>
           | <a href="#IRIrefOrFunction" title="IRIrefOrFunction">IRIrefOrFunction</a>
           | <a href="#RDFLiteral" title="RDFLiteral">RDFLiteral</a>
           | <a href="#NumericLiteral" title="NumericLiteral">NumericLiteral</a>
           | <a href="#BooleanLiteral" title="BooleanLiteral">BooleanLiteral</a>
           | <a href="#Var" title="Var">Var</a></pre>

referenced by:
         
* [UnaryExpression](#UnaryExpression "UnaryExpression")  


<a name="BrackettedExpression">BrackettedExpression:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            (Expression)



<pre><a href="#BrackettedExpression" title="BrackettedExpression">BrackettedExpression</a>
         ::= '(' <a href="#Expression" title="Expression">Expression</a> ')'</pre>

referenced by:
         
* [Constraint](#Constraint "Constraint")
* [OrderCondition](#OrderCondition "OrderCondition")
* [PrimaryExpression](#PrimaryExpression "PrimaryExpression")  


<a name="BuiltInCall">BuiltInCall:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            STR(Expression)LANG(Expression)LANGMATCHES(Expression,Expression)DATATYPE(Expression)BOUND(Var)sameTerm(Expression,Expression)isIRI(Expression)isURI(Expression)isBLANK(Expression)isLITERAL(Expression)RegexExpression



<pre><a href="#BuiltInCall" title="BuiltInCall">BuiltInCall</a>
         ::= 'STR' '(' <a href="#Expression" title="Expression">Expression</a> ')'
           | 'LANG' '(' <a href="#Expression" title="Expression">Expression</a> ')'
           | 'LANGMATCHES' '(' <a href="#Expression" title="Expression">Expression</a> ',' <a href="#Expression" title="Expression">Expression</a> ')'
           | 'DATATYPE' '(' <a href="#Expression" title="Expression">Expression</a> ')'
           | 'BOUND' '(' <a href="#Var" title="Var">Var</a> ')'
           | 'sameTerm' '(' <a href="#Expression" title="Expression">Expression</a> ',' <a href="#Expression" title="Expression">Expression</a> ')'
           | 'isIRI' '(' <a href="#Expression" title="Expression">Expression</a> ')'
           | 'isURI' '(' <a href="#Expression" title="Expression">Expression</a> ')'
           | 'isBLANK' '(' <a href="#Expression" title="Expression">Expression</a> ')'
           | 'isLITERAL' '(' <a href="#Expression" title="Expression">Expression</a> ')'
           | <a href="#RegexExpression" title="RegexExpression">RegexExpression</a></pre>

referenced by:
         
* [Constraint](#Constraint "Constraint")
* [PrimaryExpression](#PrimaryExpression "PrimaryExpression")  


<a name="RegexExpression">RegexExpression:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            REGEX(Expression,Expression,Expression)



<pre><a href="#RegexExpression" title="RegexExpression">RegexExpression</a>
         ::= 'REGEX' '(' <a href="#Expression" title="Expression">Expression</a> ',' <a href="#Expression" title="Expression">Expression</a> ( ',' <a href="#Expression" title="Expression">Expression</a> )? ')'</pre>

referenced by:
         
* [BuiltInCall](#BuiltInCall "BuiltInCall")  


<a name="IRIrefOrFunction">IRIrefOrFunction:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            IRIrefArgList



<pre><a href="#IRIrefOrFunction" title="IRIrefOrFunction">IRIrefOrFunction</a>
         ::= <a href="#IRIref" title="IRIref">IRIref</a><a href="#ArgList" title="ArgList">ArgList</a>?</pre>

referenced by:
         
* [PrimaryExpression](#PrimaryExpression "PrimaryExpression")  


<a name="RDFLiteral">RDFLiteral:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            StringLANGTAG^^IRIref



<pre><a href="#RDFLiteral" title="RDFLiteral">RDFLiteral</a>
         ::= <a href="#String" title="String">String</a> ( <a href="#LANGTAG" title="LANGTAG">LANGTAG</a> | '^^' <a href="#IRIref" title="IRIref">IRIref</a> )?</pre>

referenced by:
         
* [GraphTerm](#GraphTerm "GraphTerm")
* [PrimaryExpression](#PrimaryExpression "PrimaryExpression")  


<a name="NumericLiteral">NumericLiteral:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            NumericLiteralUnsignedNumericLiteralPositiveNumericLiteralNegative



<pre><a href="#NumericLiteral" title="NumericLiteral">NumericLiteral</a>
         ::= <a href="#NumericLiteralUnsigned" title="NumericLiteralUnsigned">NumericLiteralUnsigned</a>
           | <a href="#NumericLiteralPositive" title="NumericLiteralPositive">NumericLiteralPositive</a>
           | <a href="#NumericLiteralNegative" title="NumericLiteralNegative">NumericLiteralNegative</a></pre>

referenced by:
         
* [GraphTerm](#GraphTerm "GraphTerm")
* [PrimaryExpression](#PrimaryExpression "PrimaryExpression")  


<a name="NumericLiteralUnsigned">NumericLiteralUnsigned:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            INTEGERDECIMALDOUBLE



<pre><a href="#NumericLiteralUnsigned" title="NumericLiteralUnsigned">NumericLiteralUnsigned</a>
         ::= <a href="#INTEGER" title="INTEGER">INTEGER</a>
           | <a href="#DECIMAL" title="DECIMAL">DECIMAL</a>
           | <a href="#DOUBLE" title="DOUBLE">DOUBLE</a></pre>

referenced by:
         
* [NumericLiteral](#NumericLiteral "NumericLiteral")  


<a name="NumericLiteralPositive">NumericLiteralPositive:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            INTEGER_POSITIVEDECIMAL_POSITIVEDOUBLE_POSITIVE



<pre><a href="#NumericLiteralPositive" title="NumericLiteralPositive">NumericLiteralPositive</a>
         ::= <a href="#INTEGER_POSITIVE" title="INTEGER_POSITIVE">INTEGER_POSITIVE</a>
           | <a href="#DECIMAL_POSITIVE" title="DECIMAL_POSITIVE">DECIMAL_POSITIVE</a>
           | <a href="#DOUBLE_POSITIVE" title="DOUBLE_POSITIVE">DOUBLE_POSITIVE</a></pre>

referenced by:
         
* [AdditiveExpression](#AdditiveExpression "AdditiveExpression")
* [NumericLiteral](#NumericLiteral "NumericLiteral")  


<a name="NumericLiteralNegative">NumericLiteralNegative:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            INTEGER_NEGATIVEDECIMAL_NEGATIVEDOUBLE_NEGATIVE



<pre><a href="#NumericLiteralNegative" title="NumericLiteralNegative">NumericLiteralNegative</a>
         ::= <a href="#INTEGER_NEGATIVE" title="INTEGER_NEGATIVE">INTEGER_NEGATIVE</a>
           | <a href="#DECIMAL_NEGATIVE" title="DECIMAL_NEGATIVE">DECIMAL_NEGATIVE</a>
           | <a href="#DOUBLE_NEGATIVE" title="DOUBLE_NEGATIVE">DOUBLE_NEGATIVE</a></pre>

referenced by:
         
* [AdditiveExpression](#AdditiveExpression "AdditiveExpression")
* [NumericLiteral](#NumericLiteral "NumericLiteral")  


<a name="BooleanLiteral">BooleanLiteral:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            truefalse



<pre><a href="#BooleanLiteral" title="BooleanLiteral">BooleanLiteral</a>
         ::= 'true'
           | 'false'</pre>

referenced by:
         
* [GraphTerm](#GraphTerm "GraphTerm")
* [PrimaryExpression](#PrimaryExpression "PrimaryExpression")  


<a name="String">String:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            STRING_LITERAL1STRING_LITERAL2STRING_LITERAL_LONG1STRING_LITERAL_LONG2



<pre><a href="#String" title="String">String</a>   ::= <a href="#STRING_LITERAL1" title="STRING_LITERAL1">STRING_LITERAL1</a>
           | <a href="#STRING_LITERAL2" title="STRING_LITERAL2">STRING_LITERAL2</a>
           | <a href="#STRING_LITERAL_LONG1" title="STRING_LITERAL_LONG1">STRING_LITERAL_LONG1</a>
           | <a href="#STRING_LITERAL_LONG2" title="STRING_LITERAL_LONG2">STRING_LITERAL_LONG2</a></pre>

referenced by:
         
* [RDFLiteral](#RDFLiteral "RDFLiteral")  


<a name="IRIref">IRIref:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            IRI_REFPrefixedName



<pre><a href="#IRIref" title="IRIref">IRIref</a>   ::= <a href="#IRI_REF" title="IRI_REF">IRI_REF</a>
           | <a href="#PrefixedName" title="PrefixedName">PrefixedName</a></pre>

referenced by:
         
* [FunctionCall](#FunctionCall "FunctionCall")
* [GraphTerm](#GraphTerm "GraphTerm")
* [IRIrefOrFunction](#IRIrefOrFunction "IRIrefOrFunction")
* [RDFLiteral](#RDFLiteral "RDFLiteral")
* [SourceSelector](#SourceSelector "SourceSelector")
* [VarOrIRIref](#VarOrIRIref "VarOrIRIref")  


<a name="PrefixedName">PrefixedName:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            PNAME_LNPNAME_NS



<pre><a href="#PrefixedName" title="PrefixedName">PrefixedName</a>
         ::= <a href="#PNAME_LN" title="PNAME_LN">PNAME_LN</a>
           | <a href="#PNAME_NS" title="PNAME_NS">PNAME_NS</a></pre>

referenced by:
         
* [IRIref](#IRIref "IRIref")  


<a name="BlankNode">BlankNode:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            BLANK_NODE_LABELANON



<pre><a href="#BlankNode" title="BlankNode">BlankNode</a>
         ::= <a href="#BLANK_NODE_LABEL" title="BLANK_NODE_LABEL">BLANK_NODE_LABEL</a>
           | <a href="#ANON" title="ANON">ANON</a></pre>

referenced by:
         
* [GraphTerm](#GraphTerm "GraphTerm")  


<a name="IRI_REF">IRI_REF:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            <[^<>"{}|^`\] - [#x0000-#x0020]>



<pre><a href="#IRI_REF" title="IRI_REF">IRI_REF</a>  ::= '<' ( [^<>"{}|^`\] - [#x0000-#x0020] )* '>'</pre>

referenced by:
         
* [BaseDecl](#BaseDecl "BaseDecl")
* [IRIref](#IRIref "IRIref")
* [PrefixDecl](#PrefixDecl "PrefixDecl")  


<a name="PNAME_NS">PNAME_NS:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            PN_PREFIX:



<pre><a href="#PNAME_NS" title="PNAME_NS">PNAME_NS</a> ::= <a href="#PN_PREFIX" title="PN_PREFIX">PN_PREFIX</a>? ':'</pre>

referenced by:
         
* [PNAME_LN](#PNAME_LN "PNAME_LN")
* [PrefixDecl](#PrefixDecl "PrefixDecl")
* [PrefixedName](#PrefixedName "PrefixedName")  


<a name="PNAME_LN">PNAME_LN:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            PNAME_NSPN_LOCAL



<pre><a href="#PNAME_LN" title="PNAME_LN">PNAME_LN</a> ::= <a href="#PNAME_NS" title="PNAME_NS">PNAME_NS</a><a href="#PN_LOCAL" title="PN_LOCAL">PN_LOCAL</a></pre>

referenced by:
         
* [PrefixedName](#PrefixedName "PrefixedName")  


<a name="BLANK_NODE_LABEL">BLANK_NODE_LABEL:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            _:PN_LOCAL



<pre><a href="#BLANK_NODE_LABEL" title="BLANK_NODE_LABEL">BLANK_NODE_LABEL</a>
         ::= '_:' <a href="#PN_LOCAL" title="PN_LOCAL">PN_LOCAL</a></pre>

referenced by:
         
* [BlankNode](#BlankNode "BlankNode")  


<a name="VAR1">VAR1:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            ?VARNAME



<pre><a href="#VAR1" title="VAR1">VAR1</a>     ::= '?' <a href="#VARNAME" title="VARNAME">VARNAME</a></pre>

referenced by:
         
* [Var](#Var "Var")  


<a name="VAR2">VAR2:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            $VARNAME



<pre><a href="#VAR2" title="VAR2">VAR2</a>     ::= '$' <a href="#VARNAME" title="VARNAME">VARNAME</a></pre>

referenced by:
         
* [Var](#Var "Var")  


<a name="LANGTAG">LANGTAG:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            @[a-z][A-Z]-[a-z][A-Z][0-9]



<pre><a href="#LANGTAG" title="LANGTAG">LANGTAG</a>  ::= '@' [a-zA-Z]+ ( '-' [a-zA-Z0-9]+ )*</pre>

referenced by:
         
* [RDFLiteral](#RDFLiteral "RDFLiteral")  


<a name="INTEGER">INTEGER:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            [0-9]



<pre><a href="#INTEGER" title="INTEGER">INTEGER</a>  ::= [0-9]+</pre>

referenced by:
         
* [INTEGER_NEGATIVE](#INTEGER_NEGATIVE "INTEGER_NEGATIVE")
* [INTEGER_POSITIVE](#INTEGER_POSITIVE "INTEGER_POSITIVE")
* [LimitClause](#LimitClause "LimitClause")
* [NumericLiteralUnsigned](#NumericLiteralUnsigned "NumericLiteralUnsigned")
* [OffsetClause](#OffsetClause "OffsetClause")  


<a name="DECIMAL">DECIMAL:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            [0-9].[0-9].[0-9]



<pre><a href="#DECIMAL" title="DECIMAL">DECIMAL</a>  ::= [0-9]+ '.' [0-9]*
           | '.' [0-9]+</pre>

referenced by:
         
* [DECIMAL_NEGATIVE](#DECIMAL_NEGATIVE "DECIMAL_NEGATIVE")
* [DECIMAL_POSITIVE](#DECIMAL_POSITIVE "DECIMAL_POSITIVE")
* [NumericLiteralUnsigned](#NumericLiteralUnsigned "NumericLiteralUnsigned")  


<a name="DOUBLE">DOUBLE:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            [0-9].[0-9]EXPONENT.[0-9]EXPONENT[0-9]EXPONENT



<pre><a href="#DOUBLE" title="DOUBLE">DOUBLE</a>   ::= [0-9]+ '.' [0-9]* <a href="#EXPONENT" title="EXPONENT">EXPONENT</a>
           | '.' [0-9]+ <a href="#EXPONENT" title="EXPONENT">EXPONENT</a>
           | [0-9]+ <a href="#EXPONENT" title="EXPONENT">EXPONENT</a></pre>

referenced by:
         
* [DOUBLE_NEGATIVE](#DOUBLE_NEGATIVE "DOUBLE_NEGATIVE")
* [DOUBLE_POSITIVE](#DOUBLE_POSITIVE "DOUBLE_POSITIVE")
* [NumericLiteralUnsigned](#NumericLiteralUnsigned "NumericLiteralUnsigned")  


<a name="INTEGER_POSITIVE">INTEGER_POSITIVE:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            +INTEGER



<pre><a href="#INTEGER_POSITIVE" title="INTEGER_POSITIVE">INTEGER_POSITIVE</a>
         ::= '+' <a href="#INTEGER" title="INTEGER">INTEGER</a></pre>

referenced by:
         
* [NumericLiteralPositive](#NumericLiteralPositive "NumericLiteralPositive")  


<a name="DECIMAL_POSITIVE">DECIMAL_POSITIVE:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            +DECIMAL



<pre><a href="#DECIMAL_POSITIVE" title="DECIMAL_POSITIVE">DECIMAL_POSITIVE</a>
         ::= '+' <a href="#DECIMAL" title="DECIMAL">DECIMAL</a></pre>

referenced by:
         
* [NumericLiteralPositive](#NumericLiteralPositive "NumericLiteralPositive")  


<a name="DOUBLE_POSITIVE">DOUBLE_POSITIVE:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            +DOUBLE



<pre><a href="#DOUBLE_POSITIVE" title="DOUBLE_POSITIVE">DOUBLE_POSITIVE</a>
         ::= '+' <a href="#DOUBLE" title="DOUBLE">DOUBLE</a></pre>

referenced by:
         
* [NumericLiteralPositive](#NumericLiteralPositive "NumericLiteralPositive")  


<a name="INTEGER_NEGATIVE">INTEGER_NEGATIVE:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            -INTEGER



<pre><a href="#INTEGER_NEGATIVE" title="INTEGER_NEGATIVE">INTEGER_NEGATIVE</a>
         ::= '-' <a href="#INTEGER" title="INTEGER">INTEGER</a></pre>

referenced by:
         
* [NumericLiteralNegative](#NumericLiteralNegative "NumericLiteralNegative")  


<a name="DECIMAL_NEGATIVE">DECIMAL_NEGATIVE:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            -DECIMAL



<pre><a href="#DECIMAL_NEGATIVE" title="DECIMAL_NEGATIVE">DECIMAL_NEGATIVE</a>
         ::= '-' <a href="#DECIMAL" title="DECIMAL">DECIMAL</a></pre>

referenced by:
         
* [NumericLiteralNegative](#NumericLiteralNegative "NumericLiteralNegative")  


<a name="DOUBLE_NEGATIVE">DOUBLE_NEGATIVE:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            -DOUBLE



<pre><a href="#DOUBLE_NEGATIVE" title="DOUBLE_NEGATIVE">DOUBLE_NEGATIVE</a>
         ::= '-' <a href="#DOUBLE" title="DOUBLE">DOUBLE</a></pre>

referenced by:
         
* [NumericLiteralNegative](#NumericLiteralNegative "NumericLiteralNegative")  


<a name="EXPONENT">EXPONENT:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            eE+-[0-9]



<pre><a href="#EXPONENT" title="EXPONENT">EXPONENT</a> ::= [eE] [+#x2D]? [0-9]+</pre>

referenced by:
         
* [DOUBLE](#DOUBLE "DOUBLE")  


<a name="STRING_LITERAL1">STRING_LITERAL1:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            '[^#x0027#x005C#x000A#x000D]ECHAR'



<pre><a href="#STRING_LITERAL1" title="STRING_LITERAL1">STRING_LITERAL1</a>
         ::= "'" ( [^#x0027#x005C#x000A#x000D] | <a href="#ECHAR" title="ECHAR">ECHAR</a> )* "'"</pre>

referenced by:
         
* [String](#String "String")  


<a name="STRING_LITERAL2">STRING_LITERAL2:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            "[^#x0022#x005C#x000A#x000D]ECHAR"



<pre><a href="#STRING_LITERAL2" title="STRING_LITERAL2">STRING_LITERAL2</a>
         ::= '"' ( [^#x0022#x005C#x000A#x000D] | <a href="#ECHAR" title="ECHAR">ECHAR</a> )* '"'</pre>

referenced by:
         
* [String](#String "String")  


<a name="STRING_LITERAL_LONG1">STRING_LITERAL_LONG1:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            ''''''[^'\]ECHAR'''



<pre><a href="#STRING_LITERAL_LONG1" title="STRING_LITERAL_LONG1">STRING_LITERAL_LONG1</a>
         ::= "'''" ( ( "'" | "''" )? ( [^'\] | <a href="#ECHAR" title="ECHAR">ECHAR</a> ) )* "'''"</pre>

referenced by:
         
* [String](#String "String")  


<a name="STRING_LITERAL_LONG2">STRING_LITERAL_LONG2:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            """"""[^"\]ECHAR"""



<pre><a href="#STRING_LITERAL_LONG2" title="STRING_LITERAL_LONG2">STRING_LITERAL_LONG2</a>
         ::= '"""' ( ( '"' | '""' )? ( [^"\] | <a href="#ECHAR" title="ECHAR">ECHAR</a> ) )* '"""'</pre>

referenced by:
         
* [String](#String "String")  


<a name="ECHAR">ECHAR:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            \tbnrf\"'



<pre><a href="#ECHAR" title="ECHAR">ECHAR</a>    ::= '\' [tbnrf\"']</pre>

referenced by:
         
* [STRING_LITERAL1](#STRING_LITERAL1 "STRING_LITERAL1")
* [STRING_LITERAL2](#STRING_LITERAL2 "STRING_LITERAL2")
* [STRING_LITERAL_LONG1](#STRING_LITERAL_LONG1 "STRING_LITERAL_LONG1")
* [STRING_LITERAL_LONG2](#STRING_LITERAL_LONG2 "STRING_LITERAL_LONG2")  


<a name="NIL">NIL:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            (WS)



<pre><a href="#NIL" title="NIL">NIL</a>      ::= '(' <a href="#WS" title="WS">WS</a>* ')'</pre>

referenced by:
         
* [ArgList](#ArgList "ArgList")
* [GraphTerm](#GraphTerm "GraphTerm")  


<a name="WS">WS:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            [#x0020][#x0009][#x000D][#x000A]



<pre><a href="#WS" title="WS">WS</a>       ::= #x0020
           | #x0009
           | #x000D
           | #x000A</pre>

referenced by:
         
* [ANON](#ANON "ANON")
* [NIL](#NIL "NIL")  


<a name="ANON">ANON:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            [WS]



<pre><a href="#ANON" title="ANON">ANON</a>     ::= '[' <a href="#WS" title="WS">WS</a>* ']'</pre>

referenced by:
         
* [BlankNode](#BlankNode "BlankNode")  


<a name="PN_CHARS_BASE">PN_CHARS_BASE:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            [A-Z][a-z][#x00C0-#x00D6][#x00D8-#x00F6][#x00F8-#x02FF][#x0370-#x037D][#x037F-#x1FFF][#x200C-#x200D][#x2070-#x218F][#x2C00-#x2FEF][#x3001-#xD7FF][#xF900-#xFDCF][#xFDF0-#xFFFD][#x10000-#xEFFFF]



<pre><a href="#PN_CHARS_BASE" title="PN_CHARS_BASE">PN_CHARS_BASE</a>
         ::= [A-Z]
           | [a-z]
           | [#x00C0-#x00D6]
           | [#x00D8-#x00F6]
           | [#x00F8-#x02FF]
           | [#x0370-#x037D]
           | [#x037F-#x1FFF]
           | [#x200C-#x200D]
           | [#x2070-#x218F]
           | [#x2C00-#x2FEF]
           | [#x3001-#xD7FF]
           | [#xF900-#xFDCF]
           | [#xFDF0-#xFFFD]
           | [#x10000-#xEFFFF]</pre>

referenced by:
         
* [PN_CHARS_U](#PN_CHARS_U "PN_CHARS_U")
* [PN_PREFIX](#PN_PREFIX "PN_PREFIX")  


<a name="PN_CHARS_U">PN_CHARS_U:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            PN_CHARS_BASE_



<pre><a href="#PN_CHARS_U" title="PN_CHARS_U">PN_CHARS_U</a>
         ::= <a href="#PN_CHARS_BASE" title="PN_CHARS_BASE">PN_CHARS_BASE</a>
           | '_'</pre>

referenced by:
         
* [PN_CHARS](#PN_CHARS "PN_CHARS")
* [PN_LOCAL](#PN_LOCAL "PN_LOCAL")
* [VARNAME](#VARNAME "VARNAME")  


<a name="VARNAME">VARNAME:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            PN_CHARS_U[0-9]PN_CHARS_U[0-9][#x00B7][#x0300-#x036F][#x203F-#x2040]



<pre><a href="#VARNAME" title="VARNAME">VARNAME</a>  ::= ( <a href="#PN_CHARS_U" title="PN_CHARS_U">PN_CHARS_U</a> | [0-9] ) ( <a href="#PN_CHARS_U" title="PN_CHARS_U">PN_CHARS_U</a> | [0-9] | #x00B7 | [#x0300-#x036F] | [#x203F-#x2040] )*</pre>

referenced by:
         
* [VAR1](#VAR1 "VAR1")
* [VAR2](#VAR2 "VAR2")  


<a name="PN_CHARS">PN_CHARS:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            PN_CHARS_U-[0-9][#x00B7][#x0300-#x036F][#x203F-#x2040]



<pre><a href="#PN_CHARS" title="PN_CHARS">PN_CHARS</a> ::= <a href="#PN_CHARS_U" title="PN_CHARS_U">PN_CHARS_U</a>
           | '-'
           | [0-9]
           | #x00B7
           | [#x0300-#x036F]
           | [#x203F-#x2040]</pre>

referenced by:
         
* [PN_LOCAL](#PN_LOCAL "PN_LOCAL")
* [PN_PREFIX](#PN_PREFIX "PN_PREFIX")  


<a name="PN_PREFIX">PN_PREFIX:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            PN_CHARS_BASEPN_CHARS.PN_CHARS



<pre><a href="#PN_PREFIX" title="PN_PREFIX">PN_PREFIX</a>
         ::= <a href="#PN_CHARS_BASE" title="PN_CHARS_BASE">PN_CHARS_BASE</a> ( ( <a href="#PN_CHARS" title="PN_CHARS">PN_CHARS</a> | '.' )* <a href="#PN_CHARS" title="PN_CHARS">PN_CHARS</a> )?</pre>

referenced by:
         
* [PNAME_NS](#PNAME_NS "PNAME_NS")  


<a name="PN_LOCAL">PN_LOCAL:</a>
               @namespace "http://www.w3.org/2000/svg";
               .line                 {fill: none; stroke: #332200;}
               .bold-line            {stroke: #140E00; shape-rendering: crispEdges; stroke-width:
               2; }
               .thin-line            {stroke: #1F1400; shape-rendering: crispEdges}
               .filled               {fill: #332200; stroke: none;}
               text.terminal         {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #140E00;
               font-weight: bold;
               }
               text.nonterminal      {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1A1100;
               }
               text.regexp           {font-family: Verdana, Sans-serif;
               font-size: 12px;
               fill: #1F1400;
               }
               rect, circle, polygon {fill: #332200; stroke: #332200;}
               rect.terminal         {fill: #FFC34D; stroke: #332200;}
               rect.nonterminal      {fill: #FFDF9E; stroke: #332200;}
               rect.text             {fill: none; stroke: none;}    
               polygon.regexp        {fill: #FFECC7; stroke: #332200;}
               
            PN_CHARS_U[0-9]PN_CHARS.PN_CHARS



<pre><a href="#PN_LOCAL" title="PN_LOCAL">PN_LOCAL</a> ::= ( <a href="#PN_CHARS_U" title="PN_CHARS_U">PN_CHARS_U</a> | [0-9] ) ( ( <a href="#PN_CHARS" title="PN_CHARS">PN_CHARS</a> | '.' )* <a href="#PN_CHARS" title="PN_CHARS">PN_CHARS</a> )?</pre>

referenced by:
         
* [BLANK_NODE_LABEL](#BLANK_NODE_LABEL "BLANK_NODE_LABEL")
* [PNAME_LN](#PNAME_LN "PNAME_LN")  


- - - - - -



<table border="0" class="signature"><tr><td style="width: 100%"> </td><td valign="top"><nobr class="signature">... generated by <a name="Railroad-Diagram-Generator" class="signature" title="http://www.bottlecaps.de/rr/ui" href="http://www.bottlecaps.de/rr/ui" target="_blank">Railroad Diagram Generator</a></nobr></td><td><a name="Railroad-Diagram-Generator" title="http://www.bottlecaps.de/rr/ui" href="http://www.bottlecaps.de/rr/ui" target="_blank">RR</a></td></tr></table>
