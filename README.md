# VSCodeSnippetsComparison

Below is the comparison between Angular 2 code snippets from [Dan Wahlin (DW)](http://blog.codewithdan.com/2016/03/19/angular-2-typescript-and-html-snippets-for-vs-code/) and [John Papa (JP)](http://www.johnpapa.net/vscode-ng-snippets/) for Visual Studio Code (VSCode).

Dan Wahlin's extension has a few more snippets than John Papa. Also in a few cases, personally, DW's extension is preferred.  

This comparison came about when I saw the difference in the number of downloads between the two. DW(1790) compared to JP (24404).

![Comparison of download numbers between DW's and JP's extension](Code Snippet Downloads.png "Comparison of download numbers between DW's and JP's extension")

Legend:  
p = Preferred  
\- = No support

|                                            |    |    |                                         | 
|--------------------------------------------|----|----|-----------------------------------------| 
|                                            | JP | DW | Comments                                | 
|**TypeScript Snippets**                                            |    |    |                                         |
| Bootstrap snippet                          |    | p  | extra imports                           | 
| Component snippet                          | p  |    | added moduleid in component declaration | 
| Component root                             | p  | -  |                                         | 
| Http module import snippet                 | -  | p  |                                         | 
| Http map() snippet                         |    | p  | nicer to read                           | 
| @Input property snippet                    | -  | p  |                                         | 
| @Output event snippet                      | -  | p  |                                         | 
| Pipe snippet                               |    | p  | strongly typed                          | 
| @Routes snippet                            | p  | p  | similar                                 | 
| Route definition snippet                   | p  | p  | similar                                 | 
| Service snippet                            | p  | p  | same                                    | 
| Observable subscribe snippet               |    | p  | nicer to read                           | 
| provide() with useClass                    | -  | p  |                                         | 
|                                            |    |    |                                         | 
| **HTML Snippets**                                           |    |    |                                         | 
| [class] binding snippet                    | -  | p  |                                         | 
| [ngClass] snippet                          | p  | p  | same                                    | 
| *ngFor snippet                             | p  | p  | same                                    | 
| ngForm snippet                             | -  | p  |                                         | 
| *ngIf snippet                              | p  | p  | same                                    | 
| [(ngModel)] binding snippet                | p  | p  | same                                    | 
| basic [routerLink] snippet                 | p  | p  | same                                    | 
| [routerLink] with router parameter snippet | -  | p  |                                         | 
| [ngSwitch] snippet                         | p  | p  | same                                    | 
| [ngStyle] snippet                          | p  | p  | same                                    | 
| <select> control using *ngFor snipppet     | -  | p  |                                         | 
| [style] binding snippet                    | -  | p  |                                         | 
