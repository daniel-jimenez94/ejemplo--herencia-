public class Personal
{
  private int _id;
  private string _Nonbre;
  private string _Apellidos;
  
  public int Id
  {
    get { return _id; }
    set { _id = value; }
  }
  
  public string Nombre
  {
    get { return _Nombre; }
    set { _Nombre = value; }
  }
  
  public string Id
  {
    get { return _Apellidos; }
    set { _Apellidos = value; }
  }
  
  public Personal(int pId, string pNombre, string pApellido)
  {
    Id = pId;
    Nomre = pNombre;
    Apellidos = pApellido;
    }
}
