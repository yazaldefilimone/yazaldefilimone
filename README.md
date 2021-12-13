``````js//
#!nodejs(Typescript)

namespace Yazalde Filimone;

class About extends Me {
   public getCurrentWorkplace(): array{
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

   public getDailyKnowledge():array {
        return [
            JavaScript::class,
            TypeScript::class,
            ReactJs::class,
            Adonijs::class,
            Sass::class,
            NextJs::class,
            C++::class,
            NestJs::class,
            Css3::class,
            Html5::class,
            Nodejs::class,
            StyledComponent::class,
        ];
    }

   public getFutureGoal():string {
        return 'I will be the above average fullStack developer.';
    }
}
