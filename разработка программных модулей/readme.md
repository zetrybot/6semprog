
тесткалькулятор 
</br>

{
    public class  Tests
    {
        [SetUp]
        public void Setup()
        {
        }

        [Test]
        public void Testsum()
        {
            // ARrange - перечислить входные данные и ожидаемый результат 
            float a = 4
            float b = 10
                float expeted = 14
                // Act - вызывать функцию, которая производит действие над данными и сохранить в фактический результат
                float actual -Class1.Sum(a, b);
            // assert - сравнить ожидаемый и фактический результат 

            Assert.AreEqual(expeted, actual);
        }


        {
            [Test]
            public void Testminus()
            {
            // ARrange - перечислить входные данные и ожидаемый результат 
            float a = 4;
            float b = 10;
            float expeted = -6;
                // Act - вызывать функцию, которая производит действие над данными и сохранить в фактический результат
                float actual -Class1.minus(a, b);
                // assert - сравнить ожидаемый и фактический результат 

                Assert.AreEqual(expeted, actual);
            }
    }
    {
 [Test]
    public void Testumn()
    {
        // Arrange - перечислить входные данные и ожидаемый результат
        float a = 4;
        float b = 10;
        float expected = 40;
        // Act - вызвать функцию, которая производит действие над данными и сохранить в факт. результат
        float actual = Class1.Umn(a, b);
        // assert - сравнить ожидаемый и фактический результат
        Assert.Pass();
        Assert.AreEqual(expected, actual);
    }
    [Test]
    public void TestDel()
    {
        // Arrange - перечислить входные данные и ожидаемый результат
        float a = 10;
        float b = 2;
        float expected = 5;
        // Act - вызвать функцию, которая производит действие над данными и сохранить в факт. результат
        float actual = Class1.Del(a, b);
        // assert - сравнить ожидаемый и фактический результат
        Assert.Pass();
        Assert.AreEqual(expected, actual);
    }
    [Test]
    public void TestDelNull()
    {
        // Arrange - перечислить входные данные и ожидаемый результат
        float a = 10;
        float b = 0;
        float expected = 0;
        // Act - вызвать функцию, которая производит действие над данными и сохранить в факт. результат
        float actual = Class1.Del(a, b);
        // assert - сравнить ожидаемый и фактический результат
        Assert.Pass();
        Assert.AreEqual(expected, actual);
    }
}
}
