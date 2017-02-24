# avalon
for Ferrari

```JAVA
public interface IAttackStrategy{
    pulic void siBi(Player player){
    }
}

```

```JAVA
public class Morgana implements IAttackStrategy{
    Player player=new player();
    Role role=new Role();
    pulic void siBiTarget(Player player){
        player.notify(player);
    }
}

```

```JAVA
public class Player{
    private boolean HP;
    private String userName;
    private long passWord;
    private Role role;

    pulic void Player(){
      
    }
    pulic void Player(Role role){
      
    }
    public String notify(player){
        if(player.getRole()=="Morgana"){
                    System.out.println(player.getBadPerson()+"know I'm Morgana."+"I will tell"+player.role(Percival)+"I'm Merlin!");
        }
        TODO..

    }
}

```

```JAVA
public class Role{
    private long id;
    private String description;
    private IAttackStrategy action;
    private Player player;
    pulic void Role(){
      
    }
    pulic void Role(player){
      
    }
    
    


    public void SiBi(Player player){
        this.action.siBiTarget(player);
        }
        

    }
}

```




```JAVA
public class avalonTest{


    public class avalonTest{
     public static void main(String[] args){
          dispatchRole();
          ightisComing();
          getAllbadPerson();
          exportSpecialPlayer();
          todo..
        }
    }

    public void dispatchRole(){
        player player1=new Player();
        player1.role=new Morgana();
        todo...//发牌
    }
    
    public void nightisComing(){
        todo...//天黑请闭眼
    }
    
    public Player getAllPlayer(){
        todo...//获取所有玩家信息
    }
    
    public List<Player> getAllbadPerson(player){
        
    }
    public Player exportSpecialPlayer(){
        System.out.println(getAllBadPerson());
    }
    
    public void doSomethingToSomeone(player){
        player().role.action.siBiTarget(player);
    }
    
    ...

    }
}

```