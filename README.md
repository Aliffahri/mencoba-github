# mencoba-github
sarana percobaan teman"

package database.Entity;
import java.io.Serializable;

/**
 *
 * 
 */

public class Order_Pembelian1 implements Serializable {    
    private int Id_Bahan;
    private String Nama_Bahan;
    private int Jumlah;
    private String Id_Supplier;
    private String Nama_Supplier;
    private String Nama_Satuan;
    private String Id_satuan;
    
    

    public int getId_Bahan() {
        return Id_Bahan;
    }

    public void setId_Bahan(int Id_Bahan) {
        this.Id_Bahan = Id_Bahan;
    }

    public String getNama_Bahan() {
        return Nama_Bahan;
    }

    public void setNama_Bahan(String nama) {
        this.Nama_Bahan =nama;
    }
    
    public int getJumlah() {
        return Jumlah;
    }

    public void setJumlah(int Jumlah) {
        this.Jumlah = Jumlah;
    }
    
    public String getNama_Supplier() {
        return Nama_Supplier;
    }

    public void setNama_Supplier(String nama) {
        this.Nama_Supplier =nama;
    }
    
    public String getId_supplier() {
        return Id_Supplier;
    }

    public void setId_Supplier(String nama) {
        this.Id_Supplier =nama;
    }
    
    public String getNama_Satuan() {
        return Nama_Satuan;
    }

    public void setNama_Satuan(String nama) {
        this.Nama_Satuan =nama;
    }
    
    public String getId_satuan() {
        return Id_satuan;
    }

    public void setId_Satuan(String nama) {
        this.Id_satuan =nama;
    }
}
