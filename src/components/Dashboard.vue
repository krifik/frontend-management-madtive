
<script>
import { useRouter } from "vue-router";
export default {
  setup() {
    const router = useRouter();
    router.push({ name: "login" });
  },
};
</script>