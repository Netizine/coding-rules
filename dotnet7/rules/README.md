# Rules suppression overview

** Suppressed symbols **
* ❌ dotnet_diagnostic.[RULE].severity = error
* ✔️ dotnet_diagnostic.[RULE].severity = none
* ☑️ dotnet_diagnostic.[RULE].severity = suggestion
* 🦡 empty / no dotnet_diagnostic line in file 


## [AsyncFixer](http://www.asyncfixer.com)

| Rule        | Area              | Decision Date | root | src | test | sample | Decision link |
|-------------|-------------------|:-------------:|:----:|:---:|:----:|:------:|---------------|
|             |                   |               |      |     |      |        |               |

## [Asyncify](https://github.com/hvanbakel/Asyncify-CSharp)

| Rule        | Area              | Decision Date | root | src | test | sample | Decision link |
|-------------|-------------------|:-------------:|:----:|:---:|:----:|:------:|---------------|
|             |                   |               |      |     |      |        |               |

## [Meziantou](https://www.meziantou.net/enforcing-asynchronous-code-good-practices-using-a-roslyn-analyzer.htm)

| Rule        | Area              | Decision Date | root | src | test | sample | Decision link |
|-------------|-------------------|:-------------:|:----:|:---:|:----:|:------:|---------------|
| MA0003      | Style             | 05-02-2021    | ☑️ | 🦡 | 🦡 | 🦡 | [link](https://github.com/meziantou/Meziantou.Analyzer/blob/main/docs/Rules/MA0003.md) |
| MA0004      | Style             | 05-02-2021    | ☑️ | 🦡 | ✔️ | 🦡 | [link](https://github.com/meziantou/Meziantou.Analyzer/blob/main/docs/Rules/MA0004.md) |
| MA0006      | Style             | 11-02-2021    | ✔️ | 🦡 | 🦡 | 🦡 | [link](https://github.com/meziantou/Meziantou.Analyzer/blob/main/docs/Rules/MA0006.md) |
| MA0016      | Style             | 05-02-2021    | ❌ | 🦡 | ✔️ | 🦡 | [link](https://github.com/meziantou/Meziantou.Analyzer/blob/main/docs/Rules/MA0016.md) |
| MA0025      | Style             | 05-02-2021    | ☑️ | 🦡 | 🦡 | 🦡 | [link](https://github.com/meziantou/Meziantou.Analyzer/blob/main/docs/Rules/MA0025.md) |
| MA0026      | Style             | 05-02-2021    | ☑️ | 🦡 | 🦡 | 🦡 | [link](https://github.com/meziantou/Meziantou.Analyzer/blob/main/docs/Rules/MA0026.md) |
| MA0028      | Style             | 05-02-2021    | ✔️ | 🦡 | 🦡 | 🦡 | [link](https://github.com/meziantou/Meziantou.Analyzer/blob/main/docs/Rules/MA0028.md) |
| MA0048      | Style             | 11-02-2021    | ❌ | 🦡 | 🦡 | 🦡 | [link](https://github.com/meziantou/Meziantou.Analyzer/blob/main/docs/Rules/MA0048.md) |

## [Microsoft - Code Analysis](https://docs.microsoft.com/en-us/dotnet/fundamentals/code-analysis/quality-rules)

| Rule        | Area              | Decision Date | root | src | test | sample | Decision link |
|-------------|-------------------|:-------------:|:----:|:---:|:----:|:------:|---------------|
| CA1014      | Design            | 05-03-2021    | ✔️ | 🦡 | 🦡 | 🦡 | [link](https://learn.microsoft.com/en-us/dotnet/fundamentals/code-analysis/quality-rules/ca1014) |
| CA1068      | Design            | 05-03-2021    | ❌ | 🦡 | ✔️ | 🦡 | [link](https://learn.microsoft.com/en-us/dotnet/fundamentals/code-analysis/quality-rules/CA1068) |
| CA1707      | Naming            | 04-12-2020    | ❌ | 🦡 | ✔️ | 🦡 | [link](https://learn.microsoft.com/en-us/dotnet/fundamentals/code-analysis/quality-rules/CA1707) |
| CA2007      | Reliability       | 05-02-2021    | ☑️ | 🦡 | ✔️ | 🦡 | [link](https://learn.microsoft.com/en-us/dotnet/fundamentals/code-analysis/quality-rules/CA2007) |
| IDE0058     | Style             | 11-02-2021    | ✔️ | 🦡 | 🦡 | 🦡 | [link](https://learn.microsoft.com/en-us/dotnet/fundamentals/code-analysis/style-rules/ide0058) |

## [Microsoft - Compiler Errors](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/compiler-messages/)

| Rule        | Area              | Decision Date | root | src | test | sample | Decision link |
|-------------|-------------------|:-------------:|:----:|:---:|:----:|:------:|---------------|
| CS4014      | Naming            | 11-02-2021    | ❌ | 🦡 | 🦡 | 🦡 | [link](https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/compiler-messages/cs4014) |

## [SecurityCodeScan](https://security-code-scan.github.io)

| Rule        | Area              | Decision Date | root | src | test | sample | Decision link |
|-------------|-------------------|:-------------:|:----:|:---:|:----:|:------:|---------------|
|             |                   |               |      |     |      |        |               |

## [StyleCop](https://github.com/DotNetAnalyzers/StyleCopAnalyzers)

| Rule        | Area              | Decision Date | root | src | test | sample | Decision link |
|-------------|-------------------|:-------------:|:----:|:---:|:----:|:------:|---------------|
| SA1009      | Spacing           | 11-12-2020    | ✔️ | 🦡 | 🦡 | 🦡 | [link](https://github.com/DotNetAnalyzers/StyleCopAnalyzers/blob/master/documentation/SA1009.md) |
| SA1101      | Documentation     | 04-12-2020    | ✔️ | 🦡 | 🦡 | 🦡 | [link](https://github.com/DotNetAnalyzers/StyleCopAnalyzers/blob/master/documentation/SA1101.md) |
| SA1122      | Readability       | 05-02-2021    | ❌ | 🦡 | ✔️ | 🦡 | [link](https://github.com/DotNetAnalyzers/StyleCopAnalyzers/blob/master/documentation/SA1122.md) |
| SA1133      | Readability       | 05-02-2021    | ❌ | 🦡 | ✔️ | 🦡 | [link](https://github.com/DotNetAnalyzers/StyleCopAnalyzers/blob/master/documentation/SA1133.md) |
| SA1200      | Documentation     | 04-12-2020    | ✔️ | 🦡 | 🦡 | 🦡 | [link](https://github.com/DotNetAnalyzers/StyleCopAnalyzers/blob/master/documentation/SA1200.md) |
| SA1201      | Ordering Rules    | 05-02-2021    | ✔️ | 🦡 | 🦡 | 🦡 | [link](https://github.com/DotNetAnalyzers/StyleCopAnalyzers/blob/master/documentation/SA1201.md) |
| SA1202      | Ordering Rules    | 05-02-2021    | ✔️ | 🦡 | 🦡 | 🦡 | [link](https://github.com/DotNetAnalyzers/StyleCopAnalyzers/blob/master/documentation/SA1202.md) |
| SA1204      | Ordering Rules    | 05-02-2021    | ✔️ | 🦡 | 🦡 | 🦡 | [link](https://github.com/DotNetAnalyzers/StyleCopAnalyzers/blob/master/documentation/SA1204.md) |
| SA1413      | Maintainability   | 27-11-2020    | ❌ | 🦡 | 🦡 | 🦡 | [link](https://github.com/DotNetAnalyzers/StyleCopAnalyzers/blob/master/documentation/SA1413.md) |
| SA1600      | Documentation     | 04-12-2020    | ✔️ | 🦡 | 🦡 | 🦡 | [link](https://github.com/DotNetAnalyzers/StyleCopAnalyzers/blob/master/documentation/SA1600.md) |
| SA1602      | Documentation     | 04-12-2020    | ✔️ | 🦡 | 🦡 | 🦡 | [link](https://github.com/DotNetAnalyzers/StyleCopAnalyzers/blob/master/documentation/SA1602.md) |
| SA1604      | Documentation     | 04-12-2020    | ✔️ | 🦡 | 🦡 | 🦡 | [link](https://github.com/DotNetAnalyzers/StyleCopAnalyzers/blob/master/documentation/SA1604.md) |
| SA1623      | Documentation     | 04-12-2020    | ✔️ | 🦡 | 🦡 | 🦡 | [link](https://github.com/DotNetAnalyzers/StyleCopAnalyzers/blob/master/documentation/SA1623.md) |
| SA1629      | Documentation     | 11-02-2021    | ✔️ | 🦡 | 🦡 | 🦡 | [link](https://github.com/DotNetAnalyzers/StyleCopAnalyzers/blob/master/documentation/SA1629.md) |
| SA1633      | Documentation     | 04-12-2020    | ✔️ | 🦡 | 🦡 | 🦡 | [link](https://github.com/DotNetAnalyzers/StyleCopAnalyzers/blob/master/documentation/SA1633.md) |
| SA1649      | Documentation     | 05-03-2021    | ❌ | 🦡 | 🦡 | 🦡 | [link](https://github.com/DotNetAnalyzers/StyleCopAnalyzers/blob/master/documentation/SA1649.md) |

## [SonarAnalyzer.CSharp](https://rules.sonarsource.com/csharp)

| Rule        | Area              | Decision Date | root | src | test | sample | Decision link |
|-------------|-------------------|:-------------:|:----:|:---:|:----:|:------:|---------------|
| S1135       | ?                 | 20-12-2020    | ☑️ | 🦡 | 🦡 | 🦡 | [link](https://rules.sonarsource.com/csharp/RSPEC-1135) |
