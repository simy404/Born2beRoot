## 👋 Welcome to the Born2beRoot project
**Bu kaynak, Born2beRoot projesini yaparken öğrendiklerimi ve deneyimlerimi içermektedir.**

## İçindekiler
1. [Sanallaştırma Temelleri](#sanallaştırma-temelleri)
    - 1.1. [Sanallaştırmanın Tarihçesi ve Gelişimi](#sanallaştırmanın-tarihçesi-ve-gelişimi)
        - 1.1.1. [Sanallaştırma teknolojisinin nasıl ortaya çıktı ?](#sanallaştırma-teknolojisinin-nasıl-ortaya-çıktığını-öğren)
        - 1.1.2. [Modern sanallaştırma çözümlerinin tarihsel gelişimi](#modern-sanallaştırma-çözümlerinin-tarihsel-gelişimi)
    - 1.2. [Sanallaştırma nedir ve neden kullanılır?](#sanallaştırma-nedir-ve-neden-kullanılır)
        - 1.2.1. [Fiziksel donanım üzerinde birden fazla işletim sistemi çalıştırmanın avantajları](#fiziksel-donanım-üzerinde-birden-fazla-işletim-sistemi-çalıştırmanın-avantajları)
        - 1.2.2. [Host (Ana Makine) ve Guest (Misafir Makine) arasındaki ilişki](#host-ana-makine-ve-guest-misafir-makine-arasındaki-ilişki)
        - 1.2.3. [Sanallaştırma türleri](#sanallaştırma-türleri)
    - 1.3. [Hypervisor nedir?](#hypervisor-nedir)
        - 1.3.1. [Type 1 ve Type 2 Hypervisor farkları](#type-1-ve-type-2-hypervisor-farkları)
        - 1.3.2. [Overcommitment (kaynakların fazla tahsisi)](#overcommitment-kaynakların-fazla-tahsisi)


## 📖 Bazı Terimlerin Açıklamaları

   - **Fiziksel Makine (Physical Machine):** Gerçek donanıma sahip olan bilgisayar.
   - **Sanal Makine (Virtual Machine):** Fiziksel makine üzerinde çalışan, sanallaştırma yazılımı ile oluşturulan sanal bir bilgisayar.
   - **Hypervisor:** Sanallaştırma yazılımıdır. Fiziksel makine üzerinde çalışarak sanal makinelerin oluşturulmasını ve yönetilmesini sağlar.
   - **Sanallaştırma:** Fiziksel donanım üzerinde birden fazla işletim sistemi çalıştırılmasını sağlayan teknolojidir.
   - **Host (Ana Makine):** Hypervisor yazılımının çalıştığı fiziksel makinedir.
   - **Guest (Misafir Makine):** Hypervisor yazılımı üzerinde çalışan sanal makinelerdir.
   - **ISO Dosyası:** Bir CD veya DVD'nin birebir dijital kopyasını içeren dosya formatıdır. Genellikle işletim sistemi yüklemeleri veya yazılım dağıtımı için kullanılır. ISO dosyası, sanal makinelere veya emülatörlere bağlanarak bir disk sürücüsü gibi davranabilir.

## 📜 1. Sanallaştırma Temelleri
  - [Sanallaştırma Nedir ? AWS](https://aws.amazon.com/tr/what-is/virtualization/?utm_source=chatgpt.com)
  - [Sanallaştırma Nedir ? IBM](https://www.ibm.com/topics/virtualization)
  - [Hypervizör Nedir ?](https://aws.amazon.com/what-is/hypervisor/)
  - [Type 1 ve Type 2 Hypervisor farkları](https://aws.amazon.com/tr/compare/the-difference-between-type-1-and-type-2-hypervisors/)
  - [Belleğin Sanallaştırılması](https://www.alibabacloud.com/blog/599058)
  - [CPU'nun Sanallaştırılması](https://www.flackbox.com/virtual-processor-scheduling-how-vmware-and-microsoft-hypervisors-work-at-the-cpu-level)
