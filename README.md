``````ts//
namespace Yazalde Filimone;

class About extends Me {
   public getCurrentWorkplace(): Array{
        return [
            'workplace':[
                {
                'company' : 'Freelancer'
                },
                {
                'position' :'Júnior'
                }         
            ]
        ];
    }
  public getDailyKnowledge():Array {
        return [
           { "JavaScript": "class" },
           { "TypeScript":"class" },
           { "ReactJs":"class" },
           { "Adonijs":"class" },
           { "Sass":"class" },
           { "NextJs":"class" },
           { "C++":"class" },
           { "NestJs":"class" },
           { "Css3":"class" },
           { "Html5":"class" },
           { "Nodejs":"class"} ,
           { "StyledComponent":"class" }
        ];
    }
   public getFutureGoal():string {
        return 'I will be the above average fullStack developer.';
    }
}
