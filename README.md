```
#!nodejs

namespace Yazalde Filimone;

class About extends Me {
    getCurrentWorkplace(){
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

    getDailyKnowledge() {
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

    getFutureGoal() {
        return 'I will be the above average fullStack developer.';
    }
}
```
