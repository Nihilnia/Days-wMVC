# Days-wMVC
MVC Exercises for future mySelf

<h2> 1- AutoMapper </h2>
<div>
  <h3> // Creating Map </h3>
        <p>var config = new MapperConfiguration(cfg => {cfg.CreateMap<'sourceModel', 'destModel'>();}); <br/>
    IMapper mapper = config.CreateMapper();</p>

  <h3> // Using Map </h3>
        <p>var dest = mapper.Map<'sourceModel', 'destModel'>('sourceObject'); </p>
</div>
