## Hi, i'm Sonu! <img src="https://media.giphy.com/media/iigp4VDyf5dCLRlGkm/giphy.gif" width="30">


```rs
    struct Resume<'a> {
        code: Vec<&'a str>,
        architecture: Vec<&'a str>,
        frontend: Vec<&'a str>,
        backend: Vec<&'a str>,
        database: Vec<&'a str>,
        current_task: Vec<&'a str>,
        hotel: &'a str,
    }

    let mut sonu = Resume {
        code: vec!["Javascript", "TypeScript", "Rust", "Python", "HTML", "CSS"],
        architecture: vec!["Monolithic", "Microservice", "Layered"],
        frontend: vec!["React", "NextJS", "TailwindCSS", "ChakraUI"],
        backend: vec!["Node", "Express"],
        database: vec!["PostgreSQl", "MySql", "MongoDB", "Redis"],
        current_task: vec![],
        hotel: "trivago",
    };

    sonu.current_task.push("survive 2022!");

    sonu.current_task
        .into_iter()
        .for_each(|x| println!("{}", x));
```

